# NoteThat Electron

¡Bienvenido a NoteThat Electron! Esta es una aplicación de escritorio construida con Electron para tomar notas, entre otras funcionalidades.

## Clonar el Repositorio

Para comenzar, clona este repositorio en tu máquina local utilizando el siguiente comando:

```bash
git clone https://github.com/Diegobc21/notethat-electron.git
```

## Instalación

Una vez que hayas clonado el repositorio, navega hasta el directorio del proyecto e instala las dependencias utilizando npm:

```bash
cd notethat-electron
npm install
```

## Ejecución

Para ejecutar la aplicación en modo de desarrollo, puedes utilizar el siguiente comando:

```bash
npm start
```

Esto compilará los archivos TypeScript (si es necesario) y luego iniciará la aplicación de Electron.

## Compilación

Para compilar la aplicación y generar archivos ejecutables para diferentes plataformas, puedes utilizar el siguiente comando:

```bash
npm run build
```

Este comando compilará los archivos TypeScript (si es necesario) y luego utilizará `electron-builder` para crear instaladores y paquetes de distribución para Windows, macOS y Linux en el directorio `dist`.

## Instalación de la Aplicación

Una vez que hayas compilado la aplicación, puedes encontrar los instaladores y paquetes de distribución en el directorio `dist`. Simplemente sigue las instrucciones de instalación correspondientes a tu sistema operativo para instalar la aplicación.

¡Disfruta de NoteThat!
