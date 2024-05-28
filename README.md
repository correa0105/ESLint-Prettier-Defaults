# Utilizando Prettier e ESLint Juntos

Neste guia, vamos explorar como configurar o Prettier e o ESLint em conjunto para otimizar a qualidade e a consistência do código em projetos JavaScript.

## Pré-requisitos

Antes de começarmos, certifique-se de que você tenha instalado a extensão do ESLint no seu Visual Studio Code e configurado as seguintes opções em seu `Settings.json`:

```json
"editor.codeActionsOnSave": {
  "source.fixAll.eslint": "explicit"
}
```

## Selecionando o Modelo e Utilizando

Primeiramente, escolha a pasta que corresponde ao modelo que deseja utilizar, por exemplo, "Backend".

Agora, determine se vai trabalhar com JavaScript ou TypeScript. Baixe todos os arquivos do repositório selecionado e coloque-os dentro da pasta inicial do seu projeto. Em seguida, execute o comando `npm i` para instalar todas as dependências listadas no `package.json`. Isso garantirá que o Prettier funcione em conjunto com o ESLint. Lembre-se de que os arquivos contendo as configurações já estão incluídos no repositório.
