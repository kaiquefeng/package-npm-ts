O pacote **package-npm-ts** é um boilerplate que facilita a criação de uma estrutura de arquivos para você criar seu próprio pacote utilizando typescript.

- É necessário ter o Node instalado em sua máquina

## Como utilizar

No terminal iremos utilizar o comando:

```bash
npx package-npm-ts package-name
```

após rodar o comando ele irá fazer download dos arquivos do projeto e a instalação de dependências, quando for concluído você pode entrar na pasta do seu projeto usando o comando:

```bash
cd package-name
```

e abrir em um editor de prefência, nesse caso iremos utilizar o VSCode:

```bash
code .
```

Inicie o porjeto com git para que você possa ja adicionar ao seu github

```bash
git init
```

- Não esqueça de criar um repositório no git e adicionar ao projeto.

A estrutura de arquivos que temos é essa:

![estrutura.png](https://media.graphassets.com/97lkHX7aTNSZGMfnZmfT)

contendo apenas uma `index.ts` que é o arquivo principal e uma pasta de `test` que contém um teste unitário, além das configurações de lint e prettier que ja virá configurada.

Como você estará criando seu próprio pacote, precisamo editar o `package.json`, então basta abrir o arquivo e adicionar as informações do seu pacote, principalmente o nome que irá utilizar.

Bom, aqui a criatividade é com você para criar o que quiser com o pacote.

## Publicando no NPM

Agora nós iremos publicar o pacote na sua conta do NPM.

Vamos confirmar e enviar o código para o git

```bash
git add -A && git commit -m "Setup Package"
```

Crie sua conta no [NPM](https://www.npmjs.com/signup)

Agora no terminal do projeto rode o comando:

```
npm login
```

e adicione suas credenciais para logar, dando tudo certo basta rodar o próximo comando:

```
npm publish
```

E pronto! pacote publicado com sucesso

![Captura de Tela 2022-08-21 às 17.19.40.png](https://media.graphassets.com/c4zyEuvtSb6g3LYRXEhZ)

[https://www.npmjs.com/package/package-name-tutorial](https://www.npmjs.com/package/package-name-tutorial)

[Blog devexperience](https://devexperience.com.br/posts/criando-um-pacote-npm-usando-package-npm-ts)
