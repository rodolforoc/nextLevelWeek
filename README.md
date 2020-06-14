### Next Level Week
A Next Level Week foi uma semana disponibilizada pela [Rocketseat](https://rocketseat.com.br/) com muito conteúdo prático abordando as principais tecnologias do mercado, na qual desenvolvemos um projeto completo.

_________

## Sobre o Projeto

O Ecoleta é um projeto desenvolvimento na semana do meio ambiente e tem como objetivo gerenciar o processo de coleta de lixos nas cidades. Com ele, é possível ajudar pessoas a encontrarem pontos de coleta de forma mais fácil e eficiente.

![alt text](https://github.com/rodolforoc/nextLevelWeek/blob/master/web/src/assets/Ecoletaweb.png "Ecoleta Web")
![alt text](https://github.com/rodolforoc/nextLevelWeek/blob/master/web/src/assets/ecoletamobile.jpeg "Ecoleta Mobile")

_________

## Projeto

  ><p style="margin-left:5em">🏭  &nbsp;&nbsp;&nbsp;&nbsp;./server - API REST </p>
  ><p style="margin-left:5em">🔮  &nbsp;&nbsp;&nbsp;&nbsp;./web - Interface web em ReactJS</p>
  ><p style="margin-left:5em">📱 &nbsp;&nbsp;&nbsp;&nbsp;./mobile - Aplicação mobile em ReactNative </p>

_________

## Tecnologias

O projeto foi todo desenvolvido usando [TypeScript](https://www.typescriptlang.org/).

### Backend

- [Express](https://expressjs.com/pt-br/)
- [Knex](http://knexjs.org/)
- [SQLite](https://www.sqlite.org/index.html) 

### Frontend

- [React-Icons](https://react-icons.github.io/react-icons/)
- [React-Router-Dom](https://reacttraining.com/react-router/web/guides/quick-start)
- [Leaflet](https://leafletjs.com/)
- [Axios](https://github.com/axios/axios)

### Mobile

- [Expo](https://docs.expo.io/)
- [React-navigation](https://reactnavigation.org/)
- [Axios](https://github.com/axios/axios)

_________

## Instalações e usoos

Clone ou faça o downlod desse repositório:

```
# Clone o repositório
$ git clone https://github.com/rodolforoc/nextLevelWeek
```

Acesse a pasta server e rode os seguintes comandos:

```
# Acesse a pasta da Api
$ cd server/

# Instale as dependencias
$ npm install

# Execute as migrations
$ npm knex:migrate

# Rode a API Rest
$ npm run dev

# running on port 3333
```

Acesse a pasta web e rode os seguintes comandos:

```
# Acesse a pasta da interface web
$ cd web/

# Instale as dependencias
$ npm install

# Rode 
$ npm start

# running on port 3000
```

Acesse a pasta app-mobile e rode os seguintes comandos:

```
# Acesse a pasta do mobile
$ cd mobile/

# Instale as dependencias
$ npm install

# Rode 
$ npm start

# A Expo será aberta, basta digitalizar o qrcode no terminal ou na página da expo

# Para instalar a typagem das fontes utilizadas no projeeto, execute:
$ expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto

# Você pode installar o aplicativo Expo para testar no celular
```

