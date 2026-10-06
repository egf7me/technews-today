📱 TechNews Today — Portal de Tecnologia
📚 Sobre a atividade

Esta atividade tem como objetivo desenvolver uma página web utilizando HTML5 e CSS3, colocando em prática conceitos de estruturação, estilização, responsividade e organização de conteúdo.

O projeto simula um pequeno portal de notícias sobre tecnologia chamado TechNews Today, contendo uma notícia em destaque, um vídeo, uma área de inscrição em newsletter e um rodapé com informações de contato.

A proposta é praticar a criação de páginas modernas utilizando recursos nativos do HTML e técnicas de estilização do CSS.

🎯 Objetivos

Ao desenvolver este projeto, foram trabalhados os seguintes objetivos:

Criar uma página utilizando a estrutura básica do HTML5.

Utilizar elementos semânticos, como <header>, <main>, <article>, <section> e <footer>.

Criar formulários utilizando diferentes tipos de campos.

Incorporar um vídeo do YouTube utilizando <iframe>.

Utilizar CSS Grid para organizar o conteúdo.

Aplicar cores, gradientes, bordas e espaçamentos.

Criar efeitos de interação com :hover.

Utilizar conceitos de Glassmorphism.

Desenvolver uma página com design responsivo para diferentes tamanhos de tela.

🛠️ Tecnologias utilizadas
HTML5

O HTML foi utilizado para construir a estrutura e organizar os conteúdos da página.

Entre os principais elementos utilizados estão:

<header> — cabeçalho da página.

<main> — conteúdo principal.

<article> — notícia em destaque.

<section> — divisão das áreas de vídeo e newsletter.

<h1>, <h2> e <h3> — títulos.

<p> — parágrafos.

<time> — data da notícia.

<details> e <summary> — conteúdo que pode ser expandido.

<iframe> — incorporação do vídeo.

<form> — formulário da newsletter.

<input> — campo para e-mail e checkbox.

<select> e <option> — seleção da área de interesse.

<button> — botão de inscrição.

<footer> — rodapé.

CSS3

O CSS foi utilizado para definir a aparência visual da página.

Foram utilizados recursos como:

Cores e gradientes.

display: grid.

border-radius.

transition.

transform.

backdrop-filter.

Pseudo-classe :hover.

@media para responsividade.

Variáveis visuais como transparência e sombras.

Diferentes tamanhos e estilos de fonte.

📁 Estrutura do projeto

O projeto pode ser organizado da seguinte forma:

TechNews/
│
├── index.html
├── projeto10a.css
└── README.md

index.html

É o arquivo responsável pela estrutura da página e pelo conteúdo apresentado ao usuário.

projeto10a.css

É o arquivo responsável pela aparência visual, incluindo cores, tamanhos, espaçamentos, layout e efeitos.

README.md

Documento que apresenta informações sobre o projeto, seus objetivos e as tecnologias utilizadas.

🧱 Estrutura do HTML

A página começa com a declaração do HTML5:

<!DOCTYPE html>
<html lang="pt-br">


O elemento <head> contém informações importantes, como a codificação dos caracteres, a configuração para dispositivos móveis e o título da página.

O CSS externo é conectado ao HTML através de:

<link rel="stylesheet" href="projeto10a.css">


No <body>, a página é dividida em três partes principais:

Header
   ↓
Conteúdo principal
   ├── Notícia
   ├── Vídeo
   └── Newsletter
   ↓
Footer

📰 Notícia em destaque

A notícia é criada utilizando o elemento semântico <article>:

<article class="artigo-destaque">


Ela possui:

Título da notícia.

Data de publicação.

Resumo.

Opção para visualizar mais informações.

O elemento <details> permite criar uma área expansível:

<details class="leia-mais">
    <summary>Leia mais →</summary>
    <p>...</p>
</details>


Dessa maneira, o usuário pode clicar em "Leia mais" para visualizar o conteúdo adicional.

📺 Seção de vídeo

O projeto também possui uma área dedicada a conteúdo audiovisual.

O vídeo é incorporado através do elemento:

<iframe>


Isso permite exibir um vídeo hospedado no YouTube diretamente dentro da página.

No CSS, a classe .video-embed é utilizada para adicionar bordas arredondadas e uma borda colorida ao vídeo.

📧 Newsletter

A newsletter foi criada utilizando um formulário HTML:

<form>


O formulário possui:

Campo para e-mail.

Lista de áreas de interesse.

Checkbox para aceitar os termos.

Botão de inscrição.

O campo de e-mail utiliza:

<input type="email">


Isso permite que o navegador faça uma validação básica do formato do endereço informado.

O atributo required também é utilizado para impedir que determinados campos obrigatórios sejam enviados vazios.

🎨 Estilização com CSS

O projeto utiliza um tema escuro com tons de azul, roxo e rosa.

O fundo principal é definido através de:

body {
    background: #0a0e27;
    color: #e4e4e7;
}


Também são utilizados gradientes para deixar o visual mais moderno.

Por exemplo:

background: linear-gradient(135deg, #6366f1, #8b5cf6);

✨ Glassmorphism

O cabeçalho utiliza uma técnica visual conhecida como Glassmorphism.

Um dos recursos utilizados para produzir esse efeito é:

backdrop-filter: blur(10px);


Além disso, são utilizadas cores parcialmente transparentes e bordas discretas para criar uma aparência semelhante a um vidro translúcido.

🖱️ Efeitos de interação

O projeto utiliza :hover para criar efeitos quando o usuário passa o mouse sobre determinados elementos.

Na notícia:

.artigo-destaque:hover {
    transform: translateY(-5px);
}


Isso faz com que o card se mova levemente para cima.

No botão da newsletter:

.btn-inscrever:hover {
    transform: scale(1.05);
}


O botão aumenta um pouco de tamanho quando o mouse passa sobre ele.

Esses efeitos tornam a página mais interativa.

📐 Layout com CSS Grid

O conteúdo principal utiliza CSS Grid:

.conteudo {
    display: grid;
    grid-template-columns: 1fr;
}


Em telas maiores, o layout passa a utilizar duas colunas:

@media (min-width: 768px) {
    .conteudo {
        grid-template-columns: 2fr 1fr;
    }
}


Isso permite que a página se adapte ao tamanho da tela.

📱 Responsividade

A responsividade é aplicada através de uma Media Query:

@media (min-width: 768px) {
    ...
}


Em telas menores, os elementos são organizados em uma única coluna.

Em telas com pelo menos 768 pixels de largura, o conteúdo pode ser distribuído em duas colunas.

Essa técnica permite que o site tenha uma experiência melhor em:

📱 Celulares.

📱 Tablets.

💻 Notebooks.

🖥️ Computadores.

🧠 Conceitos aprendidos

Durante a realização da atividade, foram praticados conceitos importantes de desenvolvimento web:

Conceito	Aplicação
HTML5	Estrutura da página
HTML semântico	Organização do conteúdo
CSS3	Estilização
CSS Grid	Organização do layout
Media Query	Responsividade
Gradientes	Design visual
Hover	Interatividade
Transitions	Animações suaves
Transform	Movimentação e escala
Formulários	Newsletter
Iframe	Incorporação de vídeo
Details/Summary	Conteúdo expansível
Glassmorphism	Efeito visual do cabeçalho
▶️ Como executar o projeto

Crie uma pasta para o projeto.

Salve o código HTML como index.html.

Salve o código CSS como projeto10a.css.

Certifique-se de que os dois arquivos estejam na mesma pasta.

Abra o arquivo index.html em um navegador.

Não é necessário instalar programas ou bibliotecas adicionais para visualizar a página.

🔎 Observações

O projeto é uma atividade educacional e demonstra conceitos básicos e intermediários de desenvolvimento front-end.

O formulário possui uma configuração para enviar dados para subscribe.php, porém esse arquivo não está incluído no projeto apresentado. Portanto, para realizar um cadastro real, seria necessário desenvolver também a parte do servidor responsável pelo processamento das informações.

Também é possível fazer melhorias no código, como adicionar acessibilidade, validações adicionais, mais notícias e uma versão ainda mais adaptada para dispositivos móveis.

🏁 Conclusão

A criação do TechNews Today permitiu colocar em prática conhecimentos de HTML5 e CSS3, desde a construção da estrutura semântica até a criação de um design moderno e responsivo.

O projeto demonstra como HTML e CSS podem ser utilizados em conjunto para desenvolver uma página organizada, visualmente atrativa e adaptável a diferentes dispositivos.

Projeto desenvolvido para fins educacionais.
