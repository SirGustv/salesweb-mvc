<h1 align="center">💸 Sales Web MVC 💸</h1>
<p align="center">Concluído 🚀</p>

---
<h2>Tabela de conteúdo</h2>
<ul>
    <li><a href="#sobre-o-projeto">Sobre o projeto</a></li>
    <li><a href="#demonstração">Demonstração</a></li>
    <li><a href="#pré-requisitos">Pré-requisitos</a></li>
    <li><a href="#como-usar">Como usar</a></li>
    <ul>
    	<li><a href="#baixar-o-projeto">Baixar o projeto</a></li>
        <li><a href="#configurando-o-banco-de-dados-mysql"</a>Configurando banco de dados</li>
        <li><a href="#baixar-pacote-do-entity-framework-core"</a>Configurando Entity Framework Core</li>
    </ul>
    <li><a href="#tecnologias-utilizadas">Tecnologias utilizadas</a></li>
</ul>

---
<h2>Sobre o projeto</h2>
<p>💸 Sales Web MVC - Projeto utilizando o ASP.NET Core e suas ferramentas, criando um CRUD (Create, Read, Update, Delete) web de vendas, vendedores e departamentos.</p>
<p>Projeto desenvolvido durante o <a href="https://www.udemy.com/course/programacao-orientada-a-objetos-csharp/">curso de POO(programação orientada a objetos)</a>, com o intuito de utilizar os conceitos da POO com as ferramentas disponíbilizadas ao uso do ASP.NET Core. </p>

---
<h2>Demonstração</h2>
<p align="center">
    <video src="media/home-and-privacy.mp4" controls title="Home & Privacy"></video>    
    <figcaption align="center">Página Home e Privacy</figcaption>
</p><br>
<p align="center">
    <video src="media/departments.mp4" controls title="Departments"></video>
    <figcaption align="center">Página Departments (Departamentos)</figcaption>
</p><br>
<p align="center">
    <video src="media/sellers.mp4" controls title="Sellers"></video>
    <figcaption align="center">Página Sellers (Vendedores)</figcaption>
</p><br>
<p align="center">
    <video src="media/sales.mp4" controls title="Sales"></video>
    <figcaption align="center">Página Sales (Vendas)</figcaption>
</p>

---
<h2>Pré-requisitos</h2>
<p>Para utilizar e visualizar (a nível de código), será necessário atender os seguintes pré requisitos: 
<ul>
    <li>SDK  do <a href="https://dotnet.microsoft.com/pt-br/">.NET</a> versão <a href="https://dotnet.microsoft.com/en-us/download/dotnet/5.0">5.0.405</a> (patch 5.0.14);</p></li>
    <li><p>Banco de dados <a href="https://www.mysql.com/">MySql Workbench Community</a> versão <a href="https://downloads.mysql.com/archives/community/">8.0.32;</a></p></li>
    <li><p><a href="https://learn.microsoft.com/pt-br/ef/core/">Entity Framework Core</a> versão <a href="https://learn.microsoft.com/pt-br/ef/core/what-is-new/ef-core-5.0/whatsnew">5.0.17</a>.  </p></li>
</ul>

<p>Para baixar os dados, será necessário o gerenciador de versionamento <a href="https://git-scm.com/">Git</a> (sobre como baixar o projeto <a href="#baixar-o-proheto">clique aqui</a>), ou baixando os arquivos zipados(.ZIP) clicando <a href="https://github.com/SirGustv/salesweb-mvc/archive/refs/heads/main.zip">aqui</a>. Para a visualização do código, será necessário um editor de texto ou IDE (ambiente de desenvolvimento integrado), tanto o editor de texto <a href="https://code.visualstudio.com/">Visual Studio Code</a> quanto a IDE <a href="https://visualstudio.microsoft.com/pt-br/vs/community/">Visual Studio</a>.</p>

---
<h2>Como usar</h2>

###### Baixar o projeto
```bash
#clone este repositório(SSH)
$ git clone git@github.com:SirGustv/salesweb-mvc.git

#Vá para a pasta do projeto no terminal/cmd
$ cd SalesWebMVC/SalesWebMVC

#Baixe as dependências
$ dotnet build

#Para executar a aplicação
$ dotnet watch run

#para acessar o código via VSCode
$ code .
```
###### Configurando o Banco de dados MySql

> No arquivo `appsettings.json` (linha 11), estão a configuração que foi definida para o projeto ser conectado o banco de dados. Caso as informações do seu banco de dados for diferente, certifique-se de alterar para que seja compativél com as suas configurações.

###### Baixar pacote do Entity Framework Core

```powershell
#Instalando o Entity Framework Core
>dotnet add package Pomelo.EntityFrameworkCore.MySql --version 5.0.4 

#Instalando as ferramentas o Entity Framework Core
>dotnet tool install --global dotnet-ef --version 5.0.17

#Atualizando e povoando o banco de dados
>dotnet-ef database update

```

---
<h2>Tecnologias utilizadas</h2>

Framework: <a href="https://dotnet.microsoft.com/en-us/download/dotnet/5.0">.NET 5</a> ; <a href="https://learn.microsoft.com/pt-br/ef/core/">Entity Framework Core</a> 

Banco de Dados: <a href="https://www.mysql.com/">MySql Workbench Community</a>

Linguagem: <a href="https://learn.microsoft.com/en-us/dotnet/csharp/">C#</a> ; <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML">HTML</a> ; <a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS">CSS</a>

Editor: <a href="https://code.visualstudio.com/">Visual Studio Code</a>

Versionamento: <a href="https://git-scm.com/">Git</a>

