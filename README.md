# Rede SOFIA · WP3

Wiki do WP3 (Séries temporais clínicas e registros estruturados) da Rede SOFIA, publicada no GitHub Pages.

## Estrutura

```
index.html              capa da wiki
study-design/
  index.html            study design completo
  diagrama.png          o design em uma imagem
```

Cada página é um arquivo HTML autocontido, sem etapa de build. Para adicionar um documento, crie uma pasta com um `index.html` e um cartão na capa.

## Publicar

Em Settings → Pages, use a branch `main` e a pasta raiz (`/`).

## O que não entra aqui

Dados de pacientes (mesmo anonimizados), credenciais, minuta e documentos contratuais, formulários pessoais e gravações de reunião. O `.gitignore` bloqueia os formatos mais comuns, mas confira antes de cada commit.

O GitHub Pages costuma ser público mesmo com o repositório privado. Revise o conteúdo antes de publicar.
