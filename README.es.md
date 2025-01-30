# Sisyphe.io

[![Static Badge](https://img.shields.io/badge/lang-en-FF0000)](README.md) [![Static Badge](https://img.shields.io/badge/lang-fr-FF4500)](README.fr.md) [![Static Badge](https://img.shields.io/badge/lang-es-FFA500)](README.es.md) [![Static Badge](https://img.shields.io/badge/lang-it-FFD700)](README.it.md) [![Static Badge](https://img.shields.io/badge/lang-pt-FFFF00)](README.pt.md) [![Static Badge](https://img.shields.io/badge/lang-de-ADFF2F)](README.de.md) [![Static Badge](https://img.shields.io/badge/lang-ru-00FF00)](README.ru.md) [![Static Badge](https://img.shields.io/badge/lang-cn-00FFFF)](README.cn.md) [![Static Badge](https://img.shields.io/badge/lang-jp-007FFF)](README.jp.md) [![Static Badge](https://img.shields.io/badge/lang-kr-0000FF)](README.kr.md) [![Static Badge](https://img.shields.io/badge/lang-ar-4B0082)](README.ar.md)

[![Screenshot of game title menu](source/assets/img/menus/sisyphe.png)](https://sisyphe.acciaw.me)

[![Static Badge](https://img.shields.io/badge/Licencia%20de%20Código-GPL%20v3-darkgreen)](https://www.gnu.org/licenses/quick-guide-gplv3.html)
[![Static Badge](https://img.shields.io/badge/Licencia%20de%20Texto-CC%20BY--SA%204.0-blue)](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)

Sisyphe.io es un **proyecto de NSI (Ciencias Digitales y de la Computación) de último año**, ganador de los Trofeos NSI 2024 a nivel académico, creado y desarrollado con éxito por Killian MILANI, Siméon GILLET, Kylian ROUSSEAU y Arthur BARBEROUSSE.

Un **registro de cambios versión por versión** del proyecto hasta su lanzamiento está disponible en el directorio "source": [changelog.txt](source/changelog.txt).

> 📝
> Tras la conclusión de los Trofeos NSI 2024, la documentación del proyecto fue actualizada para aclarar la verdadera implicación de cada miembro del equipo. Es posible que notes diferencias entre la documentación en [el sitio web del concurso](https://trophees-nsi.fr/resultats-2024) y la de este repositorio de GitHub.

## Resumen

El juego te sumerge en una mitología griega paralela, donde el castigo impuesto por los dioses a Sísifo es vagar por un laberinto infinito, buscando rocas para empujar en agujeros dispersos por el terreno. La jugabilidad se inspira en el concepto de *Sokoban*, pero introduce numerosas **mecánicas originales**, que podrás descubrir a lo largo de **5 mundos únicos**. ¡El juego también incluye un **editor de niveles** completo y fácil de usar!

## Presentación y Demostración

> 📝
> Esta presentación también está disponible en la instancia de Peertube [Tube Sciences & Technologies](https://tube-sciences-technologies.apps.education.fr/) a través del enlace proporcionado con el proyecto.

Haz clic [aquí](https://youtu.be/KAzV44CmPmg) para acceder al video de presentación y demostración del proyecto.

## Requisitos Previos, Instalación y Despliegue

> 📝
> El proyecto tiene un **sitio web dedicado** al que puedes acceder en https://sisyphe.acciaw.me/ desde tu computadora o teléfono móvil. El código fuente del sitio web también está incluido en el repositorio del proyecto.

> 💡
> Si prefieres no instalar todo el proyecto, puedes simplemente descargar la versión ejecutable desde el [sitio web dedicado](https://sisyphe.acciaw.me) o haciendo clic [aquí](https://sisyphe.acciaw.me/windows).

> 🛑
> Antes de proceder con la instalación, asegúrate de que tu equipo tenga Windows 10 o 11.

### Pasos de Instalación

1. Instala el software Thonny en tu equipo:
   - Haz clic [aquí](https://thonny.org/) para visitar el sitio oficial de descargas.
2. Una vez instalado, descarga el código fuente del proyecto desde el [sitio web oficial](https://sisyphe.acciaw.me) o el repositorio de GitHub.
   - Asegúrate de extraer los archivos del juego en una carpeta de fácil acceso en tu equipo.
3. Abre el directorio "source" y haz doble clic en el archivo "sisyphe.io_beta_v1.0.py" o usa el menú contextual: "Clic derecho -> Abrir con -> Thonny."
4. En Thonny, instala las dependencias navegando al menú Herramientas -> Administrar Paquetes...:

![Dependencias 1](https://github.com/user-attachments/assets/fc6c5083-64af-46de-a568-6e0645de8d1c)

5. En la siguiente ventana, busca e instala los siguientes módulos: "pillow", "pil-supporter", "pygame":

![Dependencias 2](https://github.com/user-attachments/assets/28db7150-1531-4058-acbc-963e62f76edd)

6. Asegúrate de que la variable "fichier_exe" en la línea 25 del archivo Python esté configurada en "False".
7. Haz clic en el botón verde "Ejecutar script actual" o presiona F5 para iniciar el proyecto.
8. Si el proyecto no se ejecuta debido a un error de clave faltante, abre y ejecuta el archivo Python "del_save.py" ubicado en el directorio "assets" del proyecto usando Thonny.

> 🛑
> Si decides usar la versión ejecutable del juego, puede que no funcione en versiones antiguas de Windows 10. Para solucionar esto, ve al menú "Clic derecho -> Propiedades -> Compatibilidad" y permite que Windows corrija los problemas de compatibilidad por ti.
> Además, si el editor del juego no se ejecuta en la versión ejecutable, intenta crear una excepción para el programa en la configuración de tu antivirus.

## Protocolo de Uso

El juego se inicia con la ventana del menú principal, donde dos botones, "Abrir" y "Editor", están inicialmente deshabilitados.  
-> Se crea un archivo llamado "Sisyphe.io" en tu directorio "appdata/local", que contiene un archivo "settings.json" para guardar tu progreso y preferencias.
Después de ajustar la configuración a tu gusto, haz clic en el botón "Jugar" y completa todos los niveles del Mundo 1 para desbloquear las funciones de edición y familiarizarte con el juego.

**Controles dentro del juego:**

![Gameplay GIF](https://github.com/user-attachments/assets/c22ac271-f9df-46ec-990e-e7f9a136cd7b)

- Usa las teclas de movimiento para navegar por la cuadrícula del juego: "Arriba", "Derecha", "Abajo" y "Izquierda" (por defecto: Flechas de dirección).
- Presiona la tecla "Reiniciar" para reiniciar un nivel en caso de error (por defecto: R).
- Usa la tecla "Menú" para volver al menú principal (por defecto: M).

Para avanzar, colócate detrás de una roca y empújala hacia un agujero negro, como se muestra en el video anterior.  
El juego introducirá mecánicas cada vez más complejas, con tutoriales proporcionados al inicio de cada mundo.

> 💡
> ¿Atascado en un nivel? [Haz clic aquí](https://www.youtube.com/playlist?list=PLz5sgljMEZUJnqgS3YWLVvqHC81V0VvMx) para ver una lista de tutoriales para cada mundo.
> ¡Todos los niveles de todos los mundos y niveles extra han sido probados y son completamente superables!

## Vista General de la Arquitectura

El código fuente del proyecto contiene:
- Este archivo **"Read-Me"**
- Un archivo **"requirements.txt"** con las dependencias del proyecto
- Un directorio **"docs"** con la documentación técnica de 4 páginas
- Un directorio **"source"** que contiene:
   - Un archivo **"changelog.txt"** con el historial de actualizaciones del juego
   - Un archivo **"compilateur.txt"** (para ignorar) con comandos para compilar el juego en un ejecutable
   - El archivo principal del juego: **"sisyphe.io_beta_v1.0.py"**
   - Un directorio **"assets"** con:
     - Un archivo **"del_save.py"** para eliminar guardados en caso de problemas de claves
     - Un archivo **"sisyphe.io_editor_v2.0.py"** para el editor de niveles
     - Un archivo **"settings.json"** copiado en appdata/local/Sisyphe.io al primer inicio
     - Un directorio **"img"**, **"mus"**, **"niveaux"**, **"package"**, **"sfx"**, **"idees_niveaux"**, y **"site_web"** con los respectivos archivos del juego y su página web.

## Licenses

**Sokoban License:**

Sokoban® & © 1982 Thinking Rabbit Co., Ltd.  
Sokoban logo, Sokoban theme song, and Sokoban mechanics are trademarks of Thinking Rabbit Co., Ltd.  
Licensed to Unbalance Co., Ltd.  
Game Design by Hiroyuki Imabayashi.  
All Rights Reserved.

----

**Undertale Yellow license:**

Undertale Yellow is a free fan project based on Undertale by Toby Fox and Temmie Chang.   
Undertale Yellow soundtrack composed by MasterSwordRemix, Noteblock, MyNewSoundtrack, and Figburn.

---

**Sisyphe.io License:**

For more information about the licensing of this project, please refer to the badges at the very top of this documentation. Click on said badges to be redirected to the official descriptions of the licenses.
