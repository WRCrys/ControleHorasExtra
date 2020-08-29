![](https://gixnetwork.org/wp-content/uploads/2019/04/Microsoft-logo_rgb_gray-1024x459.png)
# ControleHorasExtra

![](https://img.shields.io/github/stars/wrcrys/MinhaApiCompleta.svg) ![](https://img.shields.io/github/forks/wrcrys/MinhaApiCompleta.svg) ![](https://img.shields.io/github/issues/wrcrys/MinhaApiCompleta.svg)


### Status do desenvolvimento

- [x] Desenvolvendo
- [ ] Concluído


## Comandos para o Gerenciador de Pacotes

#### Configurando o seu próprio contexto
##### Adicionando a nossa migration para criarmos o banco passando o contexto pois nessa aplicação temos dois contextos e não é entendido quando tem mais de um.

PM> `Add-Migration Initial  -Context MeuDbContext`


------------


##### Criando um script sql a partir da migration do contexto escolhido.

PM> `Script-Migration -Context MeuDbContext -v`


------------


##### Caso queria criar o banco direto use o comando abaixo.

Caso tenha mais de um contexto, escolha e passe...
PM> `Update-Database -Context MeuDbContext`

Caso não...
PM> `Update-Database`


------------