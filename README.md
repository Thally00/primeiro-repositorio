# primeiro-repositorio
Repositório que contém o Projeto de Receita Clássica Simples

Cartão de Receita Simples 🍴

Descrição do Projeto

Este projeto consiste em um cartão de apresentação de receita criado com HTML e CSS, ideal para sites culinários, portfólios ou blogs.
O exemplo incluído mostra uma Salada Grega Clássica, com imagem, título e descrição resumida.

O cartão é limpo, responsivo e fácil de replicar, podendo ser usado para múltiplas receitas.

Estrutura do Projeto
/ (raiz do projeto)
│
├─ index.html          # Página principal com o cartão de receita
├─ css/
│   └─ style.css       # Arquivo de estilos do cartão
└─ img/
    ├─ saladagrega.jpg # Imagem da receita
    └─ teste.png       # Ícone do site

Tecnologias Utilizadas

HTML5 – Estrutura do cartão.

CSS3 – Estilo, cores, fontes e layout responsivo.

Responsividade – Compatível com desktops, tablets e celulares.

Autor:

Thallya Bianka – Desenvolvedora do projeto.

📧 Contato: thallyabianka@gmail.com

Como Adicionar Novas Receitas

Para adicionar novas receitas, siga os passos abaixo:

```
Duplicar o cartão existente:

<div class="recipe-card">
  <img src="img/novaReceita.jpg" alt="Descrição da nova receita" class="recipe-image">
  <div class="recipe-content">
    <h2 class="recipe-title">Nome da Receita</h2>
    <p class="recipe-description">Descrição breve da receita, indicando sabor e principais ingredientes.</p>
  </div>
</div>

Atualizar a imagem:
Coloque a imagem da nova receita na pasta img/ e altere o src.

Alterar título e descrição:
Modifique os textos dentro de h2 e p conforme a receita.
