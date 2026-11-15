# Democrata — Domínio Total

### 👉 Abrir o site: **https://marcusdovale.github.io/democrata-dominio-total/**

Sistema de estudo e apoio de venda da loja Democrata do Pátio Central Shopping, em Patos de Minas/MG. Funciona no celular e no PC.

## Instalar no celular (vira um app, funciona sem internet)
- **Android (Chrome):** abra o link → menu ⋮ → **Adicionar à tela inicial / Instalar app**.
- **iPhone (Safari):** abra o link → botão Compartilhar → **Adicionar à Tela de Início**.

Depois de aberto uma vez com internet (de preferência no Wi-Fi: ele baixa as fotos, cerca de 2 MB), o site funciona **offline**, com fotos, o que ajuda se o sinal do shopping cair.

## O que tem no site
| Aba | Para quê |
|---|---|
| **Balcão** | O cliente quer… → 3–4 modelos com ref, cores e frase em um toque. Perguntas certas e venda adicional. Plano de 7 dias e dados da loja |
| **Modelos** | Os **57 modelos que a loja tem** (131 refs, lista de estoque de 15/11/2026), com **foto oficial** de cada cor. Cada card mostra as refs na loja com a cor da etiqueta, uma **foto do look** com o sapato, e a frase de venda |
| **Estilo** | *Monte o look*: ocasião + cor da calça → fotos dos looks, sapato, tom, cinto, meia, roupa e frase pronta |
| **Tecnologias** | Air, PULSE, Hi-Soft 32, Full Light, Ultra Light… o que é, onde está e como falar |
| **Venda** | Roteiro de 6 passos, frases por dor, objeções, o que nunca prometer, tipos de sapato |
| **Estudar** | 5 dias para aprender os modelos: lista com foto por grupo e **cartões** (vê a foto, tenta lembrar, confere). Progresso salvo. Dia 5 = prova + quiz de 14 perguntas |

O que você marca (plano, dias de estudo, recorde) fica salvo **no aparelho** em que você marcou.

## Arquivos
```
index.html            o site inteiro (dados, visual e lógica)
manifest.webmanifest  instalação como app
sw.js                 modo offline
icon.svg              ícone do app
fotos/looks/          fotos de look por modelo (ilustração feita com IA a partir da foto oficial) e COMANDOS.md
data/colecao.json     a coleção em dados (referência)
guias/                os mesmos conteúdos em texto, para ler ou imprimir
```

## Atualizar
- **Estoque mudou?** Troque a planilha `Lista_Estoque_SKU_Produtos.xlsx` e peça para recalcular. Na mão: cada modelo na lista `MODELOS` do `index.html` tem `sk` = [ref, cor da etiqueta, tom].
- **Para publicar:** no PC, dentro desta pasta:
  ```bash
  git add -A && git commit -m "Atualiza modelos" && git push
  ```
  Ou pelo próprio GitHub: abra o arquivo → ✏️ editar → *Commit changes*. Em 1–2 min o site atualiza.
- O preço fica de fora de propósito: preço muda, tecnologia não. Confira sempre na etiqueta.

Fonte: [democrata.com.br/tecnologias](https://www.democrata.com.br/tecnologias) e blog Verão 2026, conferido em 13/11/2026. Não é site oficial da marca.
