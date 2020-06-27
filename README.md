<h1 align="center">Primeiro Projeto Node</h1>

<p align="center">Projeto do segundo módulo do Bootcamp GoStack da <a href="https://rocketseat.com.br/" target="_blank">Rockeseat.</a></p>

Projeto em Typescript abordando contúdos de padrão de códigos (EditorConfig, ESLint, Prettier), parâmetros nomeados,
configurando o Visual Studio para debug em Node e ajustes para melhorar a produtividade.
Conceitos de Arquitetura de Software, estruturando o código em models, repositories, services.

### :star: Princípios abordados:
- **SoC (Separation of Concerns)**: Esse princípio zela pela separação de responsabilidades de cada arquivo. Exemplo: as rotas não devem ser responsáveis por lidar com a persistência dos dados, isso fica por conta do Repository. Já o Repository não é responsável pela tratativa das regras de negócio, isso é responsabilidade dos Services;
- **DRY (Don't Repeat Yourself)**: Esse princípio zela pelo maior reaproveitamento de código. Esse princípio não preza necessariamente pela não-repetição de código e sim regras de negócio. Exemplo: ao criar Services e Repositories, você possibilita a reutilização desses códigos no restante da aplicação;
- **SRP (Single Responsability Principle)**: Esse princípio zela que uma classe deve possuir apenas uma responsabilidade. Exemplo: Ao criar um service chamado `createTransactionService`, devemos garantir que no seu único método (execute()) seu trabalho seja **apenas** a criação de uma transação;
- **DIP (Dependency Inversion Principle)**: Esse princípio zela que uma entidade dependa apenas de abstrações, não de implementações. Exemplo: Ao atribuir ao Repository a comunicação com o Banco de dados, o Service precisa interagir apenas com essa abstração, sem precisar criar uma nova instância e realizar as ações diretamente;

### :rocket: Tecnologias
- [NodeJS](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)

### :computer: Bibliotecas e ferramentas:
- [Express](https://expressjs.com/) - Gerenciamento da API
- [EditorConfig](https://editorconfig.org/) - Padrão de Código
- [ESLint](https://eslint.org/) - Padrão de Código
- [Prettier](https://prettier.io/) - Padrão de Código
- [uuidv4](https://github.com/thenativeweb/uuidv4) - Gerador de ID
- [date-fns](https://date-fns.org/) - Manipulação de data em Javascript

### :information_source: Como Usar

Para executar corretamente esta aplicação você precisará do [Git](https://git-scm.com), [NodeJS](https://nodejs.org/en/) ou [Yarn](https://yarnpkg.com/) já instalados.

No seu terminal digite os comandos:

```bash
# Clone este repositório
$ git clone https://github.com/julionery/primeiro-projeto-node.git

# Vá para a pasta do back-end
$ cd conceitos-nodejs-react-reactnative/primeiro-projeto-node/

# Instale as dependências
$ yarn

# Inicie a aplicação
$ yarn dev:server


```

## :link: Como contribuir

- Faça um Fork do repositório,
- Faça um clone do respositório
- Crie uma branch com a sua feature
- Faça um commit com suas mudanças
- Push a sua branch
- Ir em Pull Requests do projeto original e criar uma pull request com o seu commit

## :memo: Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<h4 align="center">
    Feito com ❤ por <a href="https://www.linkedin.com/in/julio-nery/" target="_blank">Júlio Nery</a>!
    <g-emoji class="g-emoji" alias="wave" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f44b.png">👋</g-emoji>
</h4>
