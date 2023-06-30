# Cómo usar Git

Este es un breve guía sobre cómo utilizar Git, un sistema de control de versiones distribuido ampliamente utilizado para el desarrollo de software. Git permite realizar un seguimiento de los cambios en los archivos de un proyecto, colaborar con otros desarrolladores y mantener un historial de versiones del código.

## Tabla de contenidos

1. [Instalación de Git](#instalación-de-git)
2. [Configuración inicial](#configuración-inicial)
3. [Crear un nuevo repositorio](#crear-un-nuevo-repositorio)
4. [Realizar cambios](#realizar-cambios)
5. [Registrar cambios](#registrar-cambios)
6. [Revisar el historial de cambios](#revisar-el-historial-de-cambios)
7. [Trabajar con repositorios remotos](#trabajar-con-repositorios-remotos)
8. [Ramas](#ramas)
9. [Recursos adicionales](#recursos-adicionales)

## Instalación de Git

Para comenzar a utilizar Git, debes instalarlo en tu máquina. Visita el sitio web oficial de Git (https://git-scm.com/) y sigue las instrucciones de instalación para tu sistema operativo.

## Configuración inicial

Antes de comenzar a usar Git, es recomendable realizar una configuración inicial para establecer tu nombre de usuario y dirección de correo electrónico. Esto se puede hacer utilizando los siguientes comandos:

```shell
git config --global user.name "Tu Nombre"
git config --global user.email "tu@correo.com"
```

Esto asegurará que tus cambios se registren correctamente con tu identificación.

## Crear un nuevo repositorio

Para crear un nuevo repositorio de Git, puedes utilizar el siguiente comando:

```shell
git init
```

Esto creará un nuevo repositorio de Git en el directorio actual.

## Realizar cambios

Una vez que tienes un repositorio de Git, puedes realizar cambios en tus archivos. Puedes agregar nuevos archivos, modificar archivos existentes o eliminar archivos según sea necesario.

## Registrar cambios

Después de realizar cambios en tus archivos, debes registrar esos cambios en Git. Primero, utiliza el siguiente comando para ver el estado de tus archivos modificados:

```shell
git status
```

Luego, puedes agregar los archivos modificados para que se incluyan en el próximo commit utilizando el siguiente comando:

```shell
git add archivo1 archivo2
```

Para incluir todos los archivos modificados, puedes utilizar:

```shell
git add .
```

Finalmente, realiza un commit para guardar los cambios con un mensaje descriptivo:

```shell
git commit -m "Mensaje descriptivo de los cambios"
```

## Revisar el historial de cambios

Puedes ver el historial de cambios en tu repositorio utilizando el siguiente comando:

```shell
git log
```

Esto mostrará una lista de commits realizados, con información sobre el autor, fecha y mensaje de cada commit.

## Trabajar con repositorios remotos

Git permite colaborar con otros desarrolladores y trabajar con repositorios remotos. Puedes clonar un repositorio existente utilizando el siguiente comando:

```shell
git clone URL-del-repositorio
```

Esto creará una copia local del repositorio remoto en tu máquina.

## Ramas

Las ramas en Git permiten trabajar en diferentes versiones del código de manera independiente. Puedes crear una nueva rama utilizando el siguiente comando

:

```shell
git branch nombre-de-la-rama
```

Luego, puedes cambiar a la nueva rama utilizando:

```shell
git checkout nombre-de-la-rama
```

Puedes fusionar una rama con otra utilizando el siguiente comando:

```shell
git merge nombre-de-la-rama
```

Esto combinará los cambios de la rama especificada con la rama actual.

## Recursos adicionales

- [Documentación oficial de Git](https://git-scm.com/doc): La documentación oficial de Git es una excelente fuente de referencia para aprender más sobre el sistema de control de versiones y sus características.
- [Git Handbook](https://guides.github.com/introduction/git-handbook/): Una guía práctica proporcionada por GitHub que cubre los conceptos básicos de Git y proporciona ejemplos prácticos.
- [Pro Git book](https://git-scm.com/book/en/v2): Un libro completo y gratuito sobre Git escrito por Scott Chacon y Ben Straub, que cubre todos los aspectos de Git en profundidad.

Este readme proporciona solo una introducción básica a Git. A medida que profundices en el uso de Git, encontrarás muchas más características y funcionalidades que te ayudarán en tu flujo de trabajo de desarrollo.
