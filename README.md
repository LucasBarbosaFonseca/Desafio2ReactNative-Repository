# Desafio 2 React Native Bootcamp GoStack

# O que é o desafio?
Esse desafio consiste em consumir uma api desenvolvida em Node.js que contém repositórios fictícios cadastrados,
e com essa aplicação mobile React Native conseguimos consumir os repositórios fictícios cadastrados e dar curtidas neles.
Ainda não faz cadastros, alterações e exexclusões. Não está sendo usado nenhum banco de dados, 
os dados são armazenados em array. Essa pequena aplicação React Native é simplesmente para praticar os conceitos básicos de React Native.

# Antes de tudo
Antes de tudo para conseguirmos usar o mobile com React Native, temos que startar o backent com Node.js. Primeiro baixe o backend 
do repositório do desafio de Node.js https://github.com/LucasBarbosaFonseca/Desafio2NodeJs-Repository e execute seu servidor usando 
o comando abaixo com terminal em seu diretório:
### yarn

# Antes de executar a aplicação React Native:
- Conecte seu celular no notebook/pc com o cabo usb e com os dois dispositivos conectados na mesma rede wi-fi;
- Em seguida pegue o ip do seu pc/notebook, vá no arquivo api.js na pasta servives  que está na pasta src da aplicação React Native
e coloque o ip em "baseURL: 'http://SEU_IP:3333'," e salve o arquivo;
- Com o celular ligado na máquino com usb, digite no terminal o seguinte código e se aparecer escrito device na frende de um código é
possível continuar os próximos passos:
### adb devices
- Para finalmente executar o projeto, entre no terminal, navegue até a pasta raiz do projeto e execute o seguinte comando:
### react-native run-android
- Se a a aplicação não executar no celular, vá no terminal que tem um desenho grande e tecle a seguinte tecla que irá executar no celular:
### r
