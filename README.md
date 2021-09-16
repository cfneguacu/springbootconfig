<h2>Como Criar um Arquivo de Configuração para Produção e Desenvolvimento com Spring Boot</h2>

Para clonar o projeto(com GitHub Cli)
```
gh repo clone claudioneves1981/springbootconfig
```
Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto

```
http://localhost:8080/
```

Para trocar o ambiente basta alterar de prod para dev no arquivo application.properties. A mensagem irá se alterar para o perfil escolhido.
Consta dois arquivos um com a extensão "properties" para prod e "yml"  para dev, ambos podem ser usado para os testes de prod e dev, 
ficando a vontade para usar somente um tipo ou usar as duas formas properties ou yml, as configurações funcionam em ambas extensões e não se conflitam.

São necessários os seguintes pré-requisitos para a execução do projeto:

* Java 8 ou versões superiores.
* Maven
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.
* GitHub Cli instalado na sua maquina.
* Conta no GitHub para o armazenamento do seu projeto na nuvem.


Abaixo, seguem links dos principais recursos usados no projeto.

* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial do Spring Initialzr, para setup do projeto](https://start.spring.io/)
* [Site oficial do GIT](https://git-scm.com/)
* [Site oficial do GitHub](http://github.com/)
* [Github Cli](https://cli.github.com/)
