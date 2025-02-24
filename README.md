# 👩🏻‍💻Tutorial GitHub Pages👩🏻‍💻

Tutorial em Construção!

Olá!

Este é um guia prático sobre o GitHub Pages, um serviço de hospedagem de sites que permite que você publique conteúdo com base no código-fonte gerenciado em um repositório do GitHub. Aqui, você encontrará **comandos essenciais**, conceitos importantes e um passo a passo para publicar seu website forma eficiente e simples. 🚀
Muitas informações não serão abordadas, pois o intuito é fornecer apenas o essencial. Entretanto, para quaisquer dúvidas, você pode consultar o [site oficial](https://docs.github.com/pt/pages/getting-started-with-github-pages/creating-a-github-pages-site) do GitHub Pages.

Espero que gostem e que isso ajude no dia a dia de cada um! ☺️

Atensiosamente, Raissa Souza Krupek.

## Conceitos Iniciais

- O que é hospedagem? 🤔
  
Hospedagem é um serviço online que possibilita a disponibilização de um site ou aplicativo na internet. Basicamente, trata-se de um espaço em um servidor onde ficam armazenados todos os arquivos essenciais para que sua página seja acessível. Para facilitar a compreensão, podemos compará-la a um terreno: o site seria a casa construída nele, o domínio representaria o endereço e a internet funcionaria como a rua que conecta tudo.
Existem diversos serviços de hospedagem na internet e um deles é o Github Pages.

- Introdução ao GitHub Pages
  
O GitHub Pages é um serviço gratuito de hospedagem de sites estáticos diretamente a partir de um repositório do GitHub. Ele permite que você publique conteúdo de forma simples e eficiente, sem necessidade de servidores externos. Com ele, eh possivel puplicar com o domínio github.io, se estiver utilizando o GitHub free, ou mesmo [personalizar seu domínio](https://docs.github.com/pt/pages/configuring-a-custom-domain-for-your-github-pages-site). Estes e alguns outros conceitos serão melhor abordados mais a frente 😉

## Criando um repositório para seu site 📁
Antes de tudo, é importante saber que é possível criar um site do GitHub Pages em um repositório **novo** ou **existente**. Aqui, primeiramente, abordaremos a criação do website do inicio, criando um novo repositório!

**1º**- Na página inicial, vá até a opção `Criar novo repositório`

- Nesta etapa, você irá inserir as informações do projeto, como o nome do repositório, adicionar uma descrição breve e, em seguida, `criar repositório`.
  
  Observação: Se a conta do proprietário do repositório for o GitHub Free ou o GitHub Free para organizações, o repositório precisará ser **público**.

**2º**- Use o menu suspenso Proprietário para selecionar a conta que deseja atribuir como proprietário do repositório.

**3º**- Digite um nome para o repositório e uma descrição opcional.

- Se você estiver criando um site de usuário ou de organização, seu repositório precisará ser chamado `<user>.github.io` ou `<organization>.github.io`. Antes de definir o nome do repositório, é importante destacar que a **URL do site** publicado será gerada a partir da combinação do seu nome de usuário e do nome do repositório, por exemplo, `https://username.github.io/reponame/`. No entanto, caso mude de ideia, é possível alterá-lo posteriormente, ajustando a configuração do repositório e, se necessário, atualizando os links associados.
  
   Observação: Se o nome do usuário ou da organização contiver letras maiúsculas, você precisará colocá-las em minúsculas!

**4º**- Selecione Inicializar este repositório com um `README.md`.

Opcionalmente, você pode configurar um [domínio personalizado](https://docs.github.com/pt/pages/configuring-a-custom-domain-for-your-github-pages-site) para um site do GitHub Pages, o qual permitira, por exemplo, a personalização da URL de seu website, mas antes de explorar esse assunto, você deve colocar seu site em funcionamento com o domínio padrão

## Configurando seu repositório ⚙️

**1º**- No seu repositório, acesse a opção `Settings`.

**2º**- Na seção `Código e automação` da barra lateral, clique em `Pages`.

**3º**- Confugure uma fonte de publicação para o site

Você pode publicar seu site de duas formas: enviando suas alterações para um **branch específico** ou configurando um **fluxo de trabalho com GitHub Actions**.  

Se você não precisa de um controle avançado sobre a construção do site, a forma mais simples é configurar a publicação automática quando houver um **push** para um branch escolhido. Você pode definir qual **branch** e qual **pasta** serão usados como fonte de publicação.  

Por padrão, os repositórios do GitHub geralmente começam com um branch chamado `main`.

O branch pode ser qualquer um do seu repositório, e a pasta pode ser a **raiz do repositório (/**) ou a pasta **/docs** dentro desse branch. Sempre que fizer um **push** com mudanças, os arquivos da pasta escolhida serão atualizados automaticamente no seu site pelo **GitHub Pages**.

  **I.** Ainda em `Pages` em "Build e implantação", em "Fonte", selecione Fazer implantação de um branch.
  
  **II.** Em "Compilação e implantação", no menu suspenso de branch, selecione uma fonte de publicação.
  
  **III.** Opcionalmente, use o menu suspenso de pasta a fim de selecionar uma pasta para a fonte de publicação.
  
  **IV.** Clique em `Salvar`.


## Acesse sua URL 📲

## Mas por onde constru-o meu website? 🤔
