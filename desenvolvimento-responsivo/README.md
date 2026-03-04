# Página Web Responsiva com Bootstrap 5

Este projeto consiste na criação de uma **página web responsiva** utilizando o **sistema de grid do Bootstrap 5**.  
A página é composta por **cabeçalho**, **seção principal com três colunas** e **rodapé**, ajustando-se automaticamente a diferentes tamanhos de tela (celular, tablet e desktop).

## Objetivo

Demonstrar o uso prático do **Bootstrap 5 Grid System** para construção de layouts responsivos, sem a necessidade de CSS personalizado.


## Estrutura da Página

A página está organizada da seguinte forma:

- **Cabeçalho (`header`)**
  - Título do site
  - Subtítulo ou descrição

- **Conteúdo Principal (`main`)**
  - Container centralizado
  - Uma linha (`row`) com **três colunas**
  - Cada coluna contém título e texto

- **Rodapé (`footer`)**
  - Informações finais ou direitos autorais


## Comportamento Responsivo

O layout se adapta automaticamente conforme a largura da tela:
```
| Dispositivo | Comportamento das Colunas |
|-------------|---------------------------|
| Celular     | 1 coluna por linha        |
| Tablet      | 2 colunas por linha       |
| Desktop     | 3 colunas por linha       |
```


Isso é obtido com as seguintes classes do Bootstrap:

```html
col-12 col-md-6 col-lg-4
```

## Tecnologias Utilizadas

- HTML5

- Bootstrap 5 (via CDN)

## Como Executar o Projeto

1. Faça o download ou clone o repositório;
2. Abra o arquivo index.html em qualquer navegador moderno
3. Redimensione a janela do navegador para testar a responsividade

## CDN do Bootstrap Utilizado
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

### Observações

- Não é necessário instalar nenhuma dependência

- O projeto utiliza apenas classes utilitárias do Bootstrap

- Ideal para estudos iniciais de layout responsivo e frameworks CSS

## Autor

**Kaymmi Nunes Barbosa**

---
Projeto desenvolvido para fins educacionais, com foco no aprendizado de Bootstrap 5 e design responsivo.