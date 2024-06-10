# 📱 GPS_en tiempo real


Pedes clonarte este reposito sin embargo para que te funcione correctamente necesitas lo siguiente:

- Un entorno de desarrollo como Visual Studio Code 
- Para este paso pondrás Ctrl+ñ y se te abrirá un terminal y empieza clonando el repositorio con este comando:
```
  git clone "link del proyecto"
```
- Ve a la carpeta del proyecto
```
  cd "nombre del proyecto "
```

- Instala las dependencias
```
  npm install
```

 En caso de que no se haya instalado con el comando forzaremos la instalación con el siguiente comando 
```
 npm install --legacy-peer-deps
```

- Terminado de instalar todas sus dependencias iniciaremos el servidor con el siguiente comando.
```
   ionic server o npx ng serve

```

## 🛑 Tomar en cuenta 

Que si no tienes ionic puedes instalarlo con el siguiente comando:

```
  npm install -g @ionic/cli

```
Recuerda la aplicacion se despliega en


  http://localhost:4200/


Todo esto es necesario para que pueda funcionar correctamente

## Recuerda cambiar con tus credenciales del proyecto previamente creado en Firebase 

Dirígete a environments.ts y coloca tus credenciales mismas que podrás encontrar en configuración del proyecto.

```
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




Para que funcione el gps se debe añadir en la carpeta src, un index.html con este codigo

```bash
  <!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8" />
  <title>Ionic App</title>

  <base href="/" />

  <meta name="color-scheme" content="light dark" />
  <meta name="viewport" content="viewport-fit=cover, width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <meta name="format-detection" content="telephone=no" />
  <meta name="msapplication-tap-highlight" content="no" />

  <link rel="icon" type="image/png" href="assets/icon/favicon.png" />

  <!-- add to homescreen for ios -->
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="black" />

   <!-- Google Maps API -->
   <script src="[Tu API]"></script>
</head>

<body>
  <app-root></app-root>
</body>

</html>
```

Y para finalizar debes ingresar una API conseguida en google cloud

Todo esto es necesario para que pueda funcionar correctamente



![Logo](Recursos/img/maps.jpeg)





