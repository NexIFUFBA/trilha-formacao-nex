# Portal da Trilha de Formacao NEX/IF-UFBA

Este repositorio contem os arquivos estaticos (HTML5 e CSS3) do portal da **Trilha de Formacao em Extensao Universitaria** do **Nucleo de Extensao do Instituto de Fisica da Universidade Federal da Bahia (NEX/IF-UFBA)**.

## Estrutura de Arquivos

- `index.html`: Pagina inicial da colecao, com apresentacao do programa e cartoes dos volumes.
- `guia-01.html`: Volume 01 — *Primeiros Passos na Extensao Universitaria* (com sumario interativo e botao de exportacao direta para PDF).
- `assets/style.css`: Folha de estilos institucional (azul-marinho UFBA, branco e dourado) com regras de impressao em A4 (`@media print`).

## Como Adicionar Novos Guias no Futuro

1. Duplique o arquivo `guia-01.html` e renomeie para `guia-02.html` (e assim por diante).
2. Atualize o titulo, o sumario lateral (`<ul class="toc-list">`) e as secoes de conteudo.
3. No arquivo `index.html`, altere o cartao correspondente de `upcoming` para `featured`, mude o selo para `Disponivel` e adicione os links para o novo arquivo HTML.

---
**Coordenacao do Nucleo de Extensao do Instituto de Fisica (NEX/IF-UFBA)**  
Vinculado a Pro-Reitoria de Extensao, Arte e Cultura (PROEXT-AC / UFBA)  
Licenca: Creative Commons Atribuicao-NaoComercial 4.0 Internacional (CC BY-NC 4.0)
