# 😀🔥 CV Firebase

En esta carpeta podrás encontrar un cv o hoja de vida, tiene navegación entre páginas mismo que te permitirá ver en diferentes páginas información diferente.

Pedes clonarte este reposito sin embargo para que te funcione correctamente necesitas lo siguiente:

- Un entorno de desarrollo como Visual Studio Code 
- Para este paso pondrás Ctrl+ñ y se te abrirá un terminal y empieza clonando el repositorio con este comando:

  git clone "link del proyecto"

- Ve a la carpeta del proyecto

  cd "nombre del proyecto "

- Instala las dependencias

  npm install

* En caso de que no se haya instalado con el comando formaremos la instalación con el siguiente comando 

  npm instalo --legacy-peer-deps

- Terminado de instalar todas sus dependencias iniciaremos el servidor con el siguiente comando.

   ionic server o npx ng serve


## 🛑 Tomar en cuenta 

Que si no tienes ionic puedes instalarlo con el siguiente comando:


  npm install -g @ionic/cli


Recuerda la aplicacion se despliega en


  http://localhost:4200/


Todo esto es necesario para que pueda funcionar correctamente

## Recuerda cambiar con tus credenciales del proyecto previamente creado en Firebase 

Dirígete a environments.ts y coloca tus credenciales mismas que podrás encontrar en configuración del proyecto.

```js
  firebaseConfig :
  {
  apiKey: 'API_KEY',
  authDomain: 'DOMINIO',
  databaseURL: 'URL',
  projectId: 'ID',
  storageBucket: 'Storage',
  messagingSenderId: 'ID_Mensaje',
  appId: 'APP_ID',
  measurementId: 'ID_Medida'
  }
```

## 🖼️ Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

