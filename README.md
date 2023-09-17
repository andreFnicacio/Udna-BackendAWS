# AWS Healthtech Ecosystem
Repositório principal do ecossistema AWS para gerenciar a estrutura de uma Healthtech

## Configurando seu ambiente

## GitFlow

https://docs.google.com/presentation/d/1Ngb77xi64QJLaw8xK84NgC0zz-y5-WhNLx46pfGct_k/edit?usp=sharing

## Storybook

Para garantir que todos os comportamentos dos componentes estejam preenchidos, estamos usando o Storybook. Você pode executar ``yarn ios-storybook`` para o iOS ou ``yarn android-storybook`` para o ANDROID, e isso por si só mudará o aplicativo para o navegador do Storybook.

### Como criar uma história:

Cada arquivo de história deve e deve ser declarado na pasta raiz do componente e com o nome dele (por exemplo:. ``MyComponent.stories.tsx``)

### Como ver minha história no navegador:

Depois de criar uma nova história, você precisa executar ``yarn storybook`` (não é necessário manter esse comando em andamento, é apenas importante executá-lo para que o carregador de histórias seja carregado). Depois que o arquivo ``storyLoader.js`` for carregado, você poderá ver sua história no navegador do Storybook.

## Ícones
https://oblador.github.io/react-native-vector-icons/

## Depurador

[Reactotron](https://github.com/infinitered/reactotron)

Configuração do Reactotron para Android:
adb reverse tcp:9090 tcp:9090
```

This updated README reflects that the repository is for an AWS ecosystem related to Healthtech management. If you have any further changes or questions, please let me know!
