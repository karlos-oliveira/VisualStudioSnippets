# VisualStudioSnippets

Criei estes snippets para auxiliar na criação de novos microserviços (utilizando EFCore, FluentApi, etc) que seguem sempre a mesma estrutura, eles obedecem a arquitetura da empresa que trabalho portanto não são tão genéricos e os namespaces seguem uma hierarquia de pastas definidas, mas ainda assim acredito que possa ajudar alguem.

conf

Gera a estrutura de configuração de mapeamento do EF para determinada Model

irepo

Gera as interfaces Repository para um CRUD de determinada Model

repo

Gera as classes Repository para um CRUD de determinada Model

repofull

Gera a classe e interface Repository em um mesmo arquivo com métodos CRUD de determinada Model

iserv

Gera as interfaces Service para um CRUD de determinada Model

serv

Gera as classes Service para um CRUD de determinada Model

servfull

Gera a classe e interface Service em um mesmo arquivo com métodos CRUD de determinada Model

dbs

Auxilia na criação de propriedades DBSet na classe DBContext

tserv

Auxilia na injeção de dependencia do Service no metodo Configuration da classe Stautup

trepo

Auxilia na injeção de dependencia do Repository no metodo Configuration da classe Stautup

ctrl

Gera a controller com as rotas de CRUD para determinada model