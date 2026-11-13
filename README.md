# Democrata — Domínio Total

### 👉 Abrir o site: **https://marcusdovale.github.io/democrata-dominio-total/**

Sistema de estudo e apoio de venda da loja Democrata do Pátio Central Shopping, em Patos de Minas/MG. Funciona no celular e no PC.

## Instalar no celular (vira um app, funciona sem internet)
- **Android (Chrome):** abra o link → menu ⋮ → **Adicionar à tela inicial / Instalar app**.
- **iPhone (Safari):** abra o link → botão Compartilhar → **Adicionar à Tela de Início**.

Depois de aberto uma vez com internet, o site funciona **offline**, o que ajuda se o sinal do shopping cair.

## O que tem no site
| Aba | Para quê |
|---|---|
| **Início** | Recorde no quiz, plano de 7 dias (com check), regras de ouro e dados da loja |
| **Modelos** | 30 modelos com cores, look que combina e frase de venda. Marque o que **tem na loja** e filtre |
| **Estilo** | *Monte o look*: ocasião + cor da calça → sapato, tom, cinto, meia, roupa e frase pronta |
| **Tecnologias** | Air, PULSE, Ultra Light… o que é, onde está e como falar |
| **Venda** | Roteiro de 6 passos, frases por dor, objeções, o que nunca prometer, tipos de sapato |
| **Quiz** | 10 perguntas com explicação. Meta: 10/10 |

O que você marca (plano, "tem na loja", recorde) fica salvo **no aparelho** em que você marcou.

## Arquivos
```
index.html            o site inteiro (dados, visual e lógica)
manifest.webmanifest  instalação como app
sw.js                 modo offline
icon.svg              ícone do app
data/colecao.json     a coleção em dados (referência)
guias/                os mesmos conteúdos em texto, para ler ou imprimir
```

## Atualizar
- **Modelo novo na loja?** Fotografe a etiqueta (ref, cor, tecnologia) e acrescente na lista `MODELOS` dentro do `index.html` (e em `data/colecao.json`).
- **Para publicar:** no PC, dentro desta pasta:
  ```bash
  git add -A && git commit -m "Atualiza modelos" && git push
  ```
  Ou pelo próprio GitHub: abra o arquivo → ✏️ editar → *Commit changes*. Em 1–2 min o site atualiza.
- O preço fica de fora de propósito: preço muda, tecnologia não. Confira sempre na etiqueta.

Fonte: [democrata.com.br/tecnologias](https://www.democrata.com.br/tecnologias) e blog Verão 2026, conferido em 13/11/2026. Não é site oficial da marca.
