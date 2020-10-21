<div align="center">
    <img src="https://github.com/Nathan-Andrade/happy-web/blob/master/src/images/logo-icon.png?raw=true" />  <img src="https://raw.githubusercontent.com/rocketseat-education/nlw-03-omnistack/b213546a933add51d25db81650d8a62c654ea0f1/.github/logo.svg" width="200px"/>
</div>

<br />

<h2 align="center">
    NextLevelWeek #03 :rocket:
</h2>

  ![](https://img.shields.io/github/languages/count/Nathan-Andrade/happyMobile?color=%23ffd666) ![](https://img.shields.io/github/languages/top/Nathan-Andrade/happyMobile?color=%23ffd666) ![](https://img.shields.io/github/repo-size/Nathan-Andrade/happyMobile?color=%23ffd666) ![](https://img.shields.io/github/last-commit/Nathan-Andrade/happyMobile?color=%23ffd666)

<p align="center">
  
</p>


## :computer: Projeto

 Happy é uma aplicação que permite conectar pessoas e casas de acolhimento de uma forma remota e segura, onde poderam levar alegria para as crianças da melhor forma.

 <p align="center">
  <img src="https://github.com/Nathan-Andrade/happyMobile/blob/master/assets/splash.png?raw=true" height="300px"> <img src="https://github.com/Nathan-Andrade/happyMobile/blob/master/github/Screenshot_20201018-185327.png?raw=true" height="300px" width="140px"> <img src="https://github.com/Nathan-Andrade/happyMobile/blob/master/github/Screenshot_20201018-185341.png?raw=true" height="300px" width="140px"> <img src="https://github.com/Nathan-Andrade/happyMobile/blob/master/github/Screenshot_20201018-185350.png?raw=true" height="300px" width="140px"> <img src="https://github.com/Nathan-Andrade/happyMobile/blob/master/github/Screenshot_20201018-185359.png?raw=true" height="300px" width="140px"> <img src="https://github.com/Nathan-Andrade/happyMobile/blob/master/github/Screenshot_20201018-185402.png?raw=true" height="300px" width="140px">
</p>

 ## :airplane: Tecnologias e Bibliotecas

Este projeto foi desenvolvido com as seguintes tecnologias:

<details>
  <summary>Mobile</summary>

-   [React Native](https://reactnative.dev/)
-   [Expo](https://expo.io/learn)
-   [@expo/vector-icons](https://docs.expo.io/guides/icons/)
-   [expo-image-picker](https://docs.expo.io/tutorial/image-picker/#installing-expo-image-picker)
-   [Styled Components](https://styled-components.com/)
-   [Typescript](https://www.typescriptlang.org/)
-   [React Navigation](https://reactnavigation.org/)
-   [Axios](https://www.npmjs.com/package/axios)
-   [Expo Google Fonts](https://github.com/expo/google-fonts)
-   [React-native-maps](https://github.com/expo/react-native-appearance)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)

</details>

## :information_source: Como rodar a aplicação

### Requerimentos

Para rodar esta aplicação você vai precisar ter instalado:
* [Git](https://git-scm.com)
* [Node](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/)

### Mobile

Esta aplicação foi desenvolvida com Expo. É um software open-source que permite rodar React Native e facilita o processo de rodar a aplicação. [Clique aqui](https://expo.io/learn) para iniciar com o Expo.

```bash
# Entre na pasta do projeto
$ cd mobile

# Instale todas as dependências
$ yarn install
```

Para você conseguir rodar a aplicação, você vai precisar mudar o endereço em :
[api.ts](https://github.com/Nathan-Andrade/happyMobile/blob/master/src/services/api.ts)
```javascript
  baseURL: 'http://192.168.0.103:3333',
```
Coloque o ip da sua máquina local para poder ter acesso como no exemplo: 192.168.0.103.

Agora a aplicação irá rodar em qualquer lugar.

```bash
# Para rodar o aplicativo
yarn start
```

O Expo irá abrir em uma página do seu navegador e com o seu celular poderá escanear o QR Code que irá gerar

> Esta aplicação foi testada em um Samsung Galaxy Grand Duos Prime  e um Moto G2.

## :memo: Licensa

Este projeto tem uma licensa do MIT. Olhe a [Licensa](https://github.com/Nathan-Andrade/happyMobile/blob/master/package.json) para mais informações

---

Desenvolvido com ❤️ por <a href="https://www.linkedin.com/in/nathan-a-1b9436124/">Nathan de Andrade</a>.
