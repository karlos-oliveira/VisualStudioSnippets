# VisualStudioSnippets

Criei estes snippets para auxiliar na criação de novos microserviços (utilizando EFCore, FluentApi, etc) que seguem sempre a mesma estrutura, eles obedecem a arquitetura da empresa que trabalho portanto não são tão genéricos e os namespaces seguem uma hierarquia de pastas definidas, mas ainda assim acredito que possa ajudar alguem.

## Instalação

Para "instalar" os snippets no Visual Studio basta seguir os passos abaixo:

1. Baixar os arquivos deste repositório
2. Abrir o Visual Studio
3. Ir na aba "Ferramentas"
4. clicar no item "Gerenciador de Snippets de código"
5. Clicar no botão "Importar"
6. Selecionar os arquivos .snippet e clicar em "Abrir"
7. Clicar no botão "Concluir" e depois no botão "Ok"

## Atalhos

**conf**

Gera a estrutura de configuração de mapeamento do EF para determinada Model

**irepo**

Gera as interfaces Repository para um CRUD de determinada Model

**repo**

Gera as classes Repository para um CRUD de determinada Model

**repofull**

Gera a classe e interface Repository em um mesmo arquivo com métodos CRUD de determinada Model

**iserv**

Gera as interfaces Service para um CRUD de determinada Model

**serv**

Gera as classes Service para um CRUD de determinada Model

**servfull**

Gera a classe e interface Service em um mesmo arquivo com métodos CRUD de determinada Model

**dbs**

Auxilia na criação de propriedades DBSet na classe DBContext

**tserv**

Auxilia na injeção de dependencia do Service no metodo Configuration da classe Stautup

**trepo**

Auxilia na injeção de dependencia do Repository no metodo Configuration da classe Stautup

**ctrl**

Gera a controller com as rotas de CRUD para determinada model
