# Democrata — Domínio Total

Sistema de estudo para dominar a coleção Democrata e vender na loja do Pátio Central Shopping, Patos de Minas/MG.

## O que tem aqui
- **`index.html`** — site do sistema (abre no celular e no PC): busca por modelo/tecnologia/ocasião, fichas com frase de venda, tecnologias e quiz de 10 perguntas. É só abrir o arquivo ou publicar no GitHub Pages.
- **`data/colecao.json`** — toda a coleção em dados: tecnologias, linhas, modelos-âncora com ref, tipos de sapato, regras de ouro.
- **`guias/01-tecnologias-explicadas.md`** — as 8 tecnologias do dia a dia + as confusões que não pode errar.
- **`guias/02-tipos-de-sapato.md`** — Oxford, Derby, Loafer, Monk, Sider, Driver, Sapatênis + linhas.
- **`guias/03-atendimento-venda.md`** — roteiro de 6 passos, frases por dor, objeções e o que nunca prometer.
- **`guias/04-plano-7-dias.md`** — plano de 15 min/dia, 1 tema por dia.

## A coleção, em 1 minuto
- **Marca:** Democrata Calçados — brasileira, mais de 40 anos, líder em calçado masculino no Brasil. Base: couro legítimo.
- **Coleção atual:** Verão 27 / Alto Verão 27 (nov/2026). Linha feminina Democrata Ela (desde 2024).
- **Tecnologias:** Air, PULSE, Ultra Light, Full Light, Calce Fácil, Extra Soft, Dual Soft, Light, Smart Comfort (linha), Stretch, Max Memory. Materiais: Knit e couro legítimo.
- **Numeração masculina:** 37–44.
- **Loja:** Pátio Central Shopping, Praça Alexina Cândida Conceição, 05, Centro, Patos de Minas/MG — (34) 3821-3263 — seg–sáb 10h–22h, dom 12h–20h.

## Publicar no GitHub (2 min, no celular ou PC)
O repositório ainda não foi criado porque o GitHub não está logado neste servidor. Faça assim:

1. No GitHub, crie o repositório **`democrata-dominio-total`** (público ou privado, como preferir) na conta `MarcusdoVale`.
2. No PC, dentro desta pasta, rode:
   ```bash
   git init
   git add .
   git commit -m "Democrata Domínio Total: coleção, tecnologias, guias e quiz"
   git branch -M main
   git remote add origin https://github.com/MarcusdoVale/democrata-dominio-total.git
   git push -u origin main
   ```
3. Para o site ficar no ar: no GitHub, Settings → Pages → Source: Deploy from a branch → Branch: main → Save. O endereço fica `https://marcusdovale.github.io/democrata-dominio-total/`.

## Manter atualizado
- Modelo novo na loja? Fotografe a etiqueta (ref, cor, tecnologia) e acrescente em `data/colecao.json` e em `index.html` (lista `MODELOS`).
- Preço não está no sistema de propósito: preço muda, tecnologia não. Confira sempre na etiqueta da loja.
- Fonte: [democrata.com.br/tecnologias](https://www.democrata.com.br/tecnologias) e blog Verão 2026 — conferido em 13/11/2026.
