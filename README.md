Módulo 9: Aplicação Web – GoBarber

Frontend GoBarber - Sistema de barbearia para agendamento de serviços.
Passo a passo das instalações de todas as bibliotecas e plugins:
1º Passo: Criar projeto

npx create-react-app my-app ou yarn create-app my-app

2º Passo: Configurar EditorConfig

Crie o arquivo .editorconfig pelo menu de contexto do vscode.

root = true

[*]
end_of_line = lf
indent_style = space
indent_size = 2
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

3º Passo: Instalar e Configurar Eslint em ambiente de dev.

Usado para informar erros no código

yarn add eslint -D

Iniciar Configurações:

yarn add eslint –init

4º Passo: Instalar e Configurar Eslint/Prettier em Ambiente Dev.

yarn add prettier eslint-config-prettier eslint-plugin-prettier babel-eslint -D

5º Passo: Instalar React Router Dom.

Usado para navegação web

yarn add react-router-dom

6º Passo: Instalar History.

Usado para navegação entre telas

yarn add history

7º Passo: Instalar Reactotron (Usado para debug)

yarn add reactotron-react-js


8º Passo: Instalar Styled Components.

Usado para estilização das páginas

yarn add styled-components


9º Passo: Instalar Root Import em ambiente dev.

Usado para simplificar os caminhos das importações dos arquivos no app

yarn add customize-cra react-app-rewired -D

10º Passo: Instalar Polished.

Usado para trabalhar com cores dentro do plugin Styled Components

yarn add polished

11º Passo: Instalar Unform.

Biblioteca da Rocketseat para deixar mais performático os formulários

yarn add @rocketseat/unform

12º Passo: Instalar Yup.

Usado para validação front-end e back-end

yarn add yup

13º Passo: Instalar várias bibliotecas.

yarn add redux redux-saga react-redux reactotron-redux reactotron-redux-saga immer

14º Passo: Instalar Axios.

Usado para fazer requisições APIs

yarn add axios

15º Passo: Instalar Redux Persist.

Usado para armazenar dados básicos de autenticação do usuário mesmo após atualização ou fechamento do navegador

yarn add redux-persist

16º Passo: Instalar React Toastify.

Usado para apresentar notificações estilizadas

yarn add react-toastify

17º Passo: Instalar React Icons.

Biblioteca de ícones

yarn add react-icons

18º Passo: Instalar Date FNS.

Biblioteca usada para manipulação de data/hora

yarn add date-fns@next `– @next instala na atual versão`

19º Passo: Instalar Date FNS-TZ.

Biblioteca usada para lidar com Time Zones de data/hora

yarn add date-fns-tz
