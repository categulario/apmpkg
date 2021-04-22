# ApmPKG
![version](https://img.shields.io/badge/Version-v0.1--Pre--Beta-blue)![Travis (.org)](https://travis-ci.com/Kedap/apmpkg.svg?token=xg7g7bZN9YxrMVR6YKvj&branch=main)

A Package Manager as a model: PKGBUILD

# NOTICIAS
- Se ha liberado la primera versioon: v0.1-Pre-Beta (solo para beta tester)
- Creacion de la documentacion
- Creacion de los primeros graficos
* * *
Un gestor de paquetes que desea se una poderosa herramienta universal para linux con el fin de la cracion e instalacion de paquetes.
![Captura](img/captura_prin.png)

## Crear paquetes

Una herramienta escrita en rust y bash, que utiliza gestores de paquetes nativos para la resolucion de dependencias, se pueden crear paquetes desde un archivo simple con sintaxis TOML y hasta puedes de igual manera crearlo desde un PKGBUILD!
Gestores de paquetes soportado por ApmPKG

- [x] Apt
- [x] Pacman
- [x] Dnf
- [x] Snap
- [x] Flatpak
- [x] Zypper
- [ ] Emerge
- [ ] Yay
- [ ] Pkg (termux)
- [ ] Yum
- [ ] Apk

De igual manera se pueden crear binarios para instalacion offline [binarios (hacer art)] de igual manera mas [mas infomarcion aqui (hacer art)]

## Instalacion
* * * 
Aunque sea algo dificl o raro, de igual manera podemos instalar apmpkg con el mismo apmpkg, aun porque creemos que la distribucion de paquetes es importante tratamos de poner a disposicion y de crear binarios nativos para cada distribucion en donde son soportados los gestores de paquetes,  pero primero debes de tener las depencias, entre ellos: pip3/pip2, bundle, curl, fakeroot y git, para ello puedes dirijirte a la seccion de [lanzamientos(link)] en donde se suben los paquetes, si deseas tener mas informacion, [click aqui(hacer art de instalacion)]

# Caracteristicas
- Creacion de paquetes de para lenguajes de script, un claro ejemplo es python y ruby. Con soporte con pip y bundle [mas info aqui(link al de creacion de paquetes)]
- Facilidad de creacion de paquetes sobre el modelo de [PKGBUILD de archlinux](https://wiki.archlinux.org/index.php/PKGBUILD) es decir que tenemos soporte para AUR, aun que tenemos ciertas [limitaciones para decir que tenemos soporte para todos los PKGBUILD's existentes (link a creacion de paquetes)] pero de igual manera estamos trabajando en eso
- Resolucion de dependencias con los gestores de paquetes antes mencionados, trabajaremos para que la lista sea mas externa
- Descargar y/o compilar desde una url, ejemplo: `apmpkg instalar -u https://foo.com/far`
- Extenciones propios de nuestra herramienta, *.adi, .abc y .abi.tar.gz* cada una tiene una funcion especial, [mas informacion aqui (link crear paquetes)]

## Contribuir
Si tienes una buena idea o quieres contribuir con este proyecto puedes empezar por [aqui](https://github.com/Kedap/apmpkg/issues) y leer [esto(Crear art de contribucion)]

## FAQ / Preguntas frecuentes

**¿Realmente es universal para TODAS las distribuciones gnu/linux disponibles?**
No, solo para aquellas que tenemos soporte para las dependencias, gestores de paquetes y arquitectura de estos.

**¿Porque no implentan X caracteristica?**
Por lo mismo, no compartes tu idea, estaremos felices de conocer tu idea, puedes apoyar [aqui](https://github.com/Kedap/apmpkg/issues) y/o si quieres mas informacion [aqui(contri)]
