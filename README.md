<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

<blockquote align="center">“Sucesso não é o resultado de um jogo, mas o destino de uma jornada”!</blockquote>

## :rocket: Sobre o desafio

Nesse desafio, foi criado uma aplicação para treinar o que você aprendi até agora no React Native.

É uma aplicação que armazena repositórios, onde já foi desenvolvido o [backend utilizando o Node.js](https://github.com/gabrielpapke/bootcamp-gostack-desafio-02), e também no [último desafio em ReactJS](https://github.com/gabrielpapke/bootcamp-gostack-desafio-03).

### 👉 Como executar
Para este projeto mobile, é necessário que siga as instruções do [desafio 02](https://github.com/gabrielpapke/bootcamp-gostack-desafio-02) e rode o backend.

Também é necessário configurar todo ambiente para que o consiga rodar no emulador ou em seu dispositivo físico, para isso existe [essa documentação](http://react-native.rocketseat.dev/) que a rocketseat disponibilizou.

Após toda a configuração, para rodar o mobile:
1. Abra o terminal e execute o comando `yarn` no diretório do desafio, para que instale as dependências.

2. Para rodar a aplicação execute `yarn start`

3. Agora em outra janela do terminal execute `npx react-native run-ios` ou `npx react-native run-android` caso tenha configurado com emulador.

4. Caso queira rodar os testes execute `yarn test`

Enjoy it! 😁

### Funcionalidades da aplicação

- [ ] **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- [ ] **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.


## :memo: Licença

Esse projeto está sob a licença MIT.

---

Desafio feito com 💜 por [Gabriel Papke](https://linkedin.com/in/gabrielpapke/)
