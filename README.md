Projeto de Ensino de Tecnologia

- Logo do Projeto

Eu sou o Milton Bolonha, um programador e versionador de códigos. Eu estou aqui para te ensinar tecnologia de ponta.

Bem-vindo ao projeto repositório de códigos da Bolonha Conversas. Nós temos uma base sólida para iniciarmos nossas aventuras no mundo da tecnologia, utilizando a poderosa ferramenta do Github.

# Sobre o Projeto

Este repositório serve como ponto de partida para nossas atividades pedagógicas no campo da tecnologia, com foco no desenvolvimento de aplicações web modernas.

# Como Iniciar?

Eu preparei para você interagir com este capítulo, uma arquitetura de projeto real, que servirá como o seu primeiro molde.
É um repositório GitHub que serve como ponto de partida para as nossas atividades pedagógicas no campo da programação, com foco no desenvolvimento de aplicações web modernas e na hospedagem serverless do GitHub Pages. 
Os nossos passos para experimentar essa tecnologia serão:

1.	Clonar o repositório;
2.	Configurar o arquivo next.config.js:3;
3.	Enviar mudanças e comentar código;
4.	Configurar GitHub Actions;
5.	Iniciar esteira atualizando o repositório;
6.	Acessar a sua página.

## CLONAR O REPOSITÓRIO

Para começar acesse o repositório Git chamado “next-boilerplate” que se encontra no meu perfil GitHub:

_www.github.com/miltonbolonha/next-boilerplate_

Pressione o botão “Use this template”, no canto superior direito da tela e depois “Create a new repository”:

`[imagem]`

Em seguida, dê o nome ao seu repositório de “next-boilerplate”. Caso você mudar o nome do seu repositório, mais a frente você deverá fazer uma configuração adicional, como no exemplo a seguir.

“meu-primeiro-molde”
 
Então dê inicio a criação do repositório clicando em “Create repository”:

`[imagem]`

O seu repositório foi criado, para quem mudou o nome do repositório para algo customizado, temos um passo a mais, agora vamos configurar as coisas para que a sua página web comece a ser gerada.

## CONFIGURANDO O NEXT.JS

Acesse a pasta “next-boilerplate”:

`[imagem]`
 
E então abra o arquivo “next-config.js”:

`[imagem]`

Encontre o botão de editar, que é um lápis:

`[imagem]`
 
Edite a linha 3 do arquivo (next.config.js:3):

`[imagem]`
 
Confirme as mudanças clicando no botão “Commit changes” e faça um comentário sobre essa alteração:
 
## CONFIGURANDO O GITHUB PAGES

Após isso, acesse a aba Settings do seu repositório:
 
Na barra lateral esquerda, acesse “Pages”:

`[imagem]`
 
Por fim, configure o servidor GitHub Pages escolhendo a opção de montar o seu website, por meio das GitHub Actions:

`[imagem]`
 
## INICIANDO ESTEIRA DE EVENTOS

Volte a aba de código do seu projeto acessando a aba “Code”:

`[imagem]`
 
Você precisa fazer uma alteração qualquer para montar o seu website e enviá-lo ao servidor GitHub Pages. Encontre na tela inicial do seu repositório, um arquivo com o nome “package.json”.
 
Esse é um arquivo central de um repositório contendo tecnologia NodeJS. Nele vamos alterar apenas a numeração da versão atual do nosso website:

`[imagem]`
 
Edite a linha 3 (package.json:3), o número que está em “version” se refere a versão do seu website 1.0.0. Mude a versão para 1.1.0. 
Agora que você fez a primeira atualização, a esteira de eventos de construção do seu website foi iniciada.

## ACESSANDO A SUA PÁGINA

Volte a tela de código do seu repositório e agora na barra lateral direita, clique no ícone pequeno em formato de engrenagem:

`[imagem]`
 
No pop-up que aparecer, selecione na seção Website o campo “Use your GitHub Pages website/Usar meu website do GitHub Page” e então salve sua mudança acionando “Save Changes”:

`[imagem]`
 
Agora, a barra da lateral direita do seu repositório tem um link para o website que você criou:

`[imagem]`
 
Clique no endereço e aceda ao seu primeiro website moderno:

`[imagem]`
 
Se você está vendo uma tela como a de cima, parabéns, você conseguiu usar o seu primeiro Molde GitHub.

# Como Usar Via Terminal

Para começar acesse o Boilerplate Next.js do repositório de Milton Bolonha.

Use o Github Template. Acesse a página gerada no GitHub Pages. Ou inicie o servidor de desenvolvimento com o comando:

```
npm i && npm run dev --workspace=next-boilerplate
```

Acesse a aplicação em seu navegador através do endereço: http://localhost:3000.

A partir desse ponto, você estará pronto(a) para começar a desenvolver suas próprias funcionalidades sobre essa base sólida.

# Contribuições

Contribuições são sempre bem-vindas! Se você encontrar bugs, tiver sugestões ou quiser adicionar novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request. Juntos, podemos tornar esse boilerplate cada vez melhor!

## Como customizar?

Modifique o arquivo `next-boilerplate/src/pages/index.js`. A página atualizará automaticamente.

# Contato

Em caso de dúvidas ou sugestões, você pode entrar em contato através do e-mail: miltonbolonha@gmail.com
Vamos explorar o mundo da tecnologia juntos e criar projetos incríveis! 🚀
