# Proyecto de Maestria en Ingenieria de Software - UTP PORTAL DE OFERTAS

## UTP PORTAL DE OFERTAS



## Screenshots




## Flutter plugins
Flutter
Dart
Github

### Created & Maintained By Juan B Gonzalez

## Vamos a iniciar para saber los pasos de entrar en el Mundo de Flutter

1. Descargar Android Studio 
2. Conocer el tema de Android SDK C:\Users\JuanB\AppData\Local\Android\Sdk
3. Saber diferenciar entre que es el Android SDK y el Flutter SDK no es lo mismo.
4. Descargar el Flutter SDK
5. Entrar en Android Studio en Plugins descargar Flutter (Igualmente esto te obliga a descargar Dart)
6. El plugin Flutter no es un SDK solo trae los componentes acopladas al compilador, templates basicor flutter para iniciar y otras funciones (flutter Doctor) para facilitar el desarrollo el flutter.
7. Despues de descomprimir el Flutter SDK debes ponerlo en un ruta comoda dentro de tu ambiente de desarrollo de android studio por ejemplo:  
C:\Users\JuanB\AppData\Local\Android\flutter  (Aqui esta mi flutter SDK)
C:\Users\JuanB\AppData\Local\Android\Sdk    (Aqui esta mi Android SDK)
Los dos SDK los necesitamos para desarrollar , debugear , compilar y desplegar en Android o iOS 
8. Crear un maquina virtual dentro de Android Studio , el concepto debe entenderse de este modo por que android studio tambien virtualiza maquinas que este caso le llamariamos celulares. Por ejemplo ya cree un celular virtual (Maquina virtual) y le asigne el sistema operativo android pero la version Oreo 8.0 , asignandole 4.0 gb de memoria ram de mi pc, todo esto desplegado en el Google Pixel 2 que es uno bastante comun porque maneja tamanos de 1920x1080 pixeles (El celular comun)
9. Sin los pasos anteriores no podras desplegar tu codigo .dart que es para flutter


ACOPLACION LOGIN - Ajustes
1. Al abrir el nuevo proyecto de Login lo coloque en una carpeta comoda y despues de esto abri el android studio.
2. Se le indico al programa donde estaba en main.dart inicial el cual es importante.
3. Despues sale un error de Dart.sdk el cual requiere que le integre el Flutter SDK , se le asing usando el SDK MANAGER  , que lo accese desde Settings>Languages&Frameworks>Dart (Aqui le asigne la direccion del SDK de flutter ya que el SDK de flutter inclute tanto el SDK DART Y EL MISMO DE FLUTTER
4. Al ejecutar el aplicativo sale una informacion de que este material design es obsoleto y usa una version anterior
info: 'display1' is deprecated and shouldn't be used. This is the term used in the 2014 version of material design. The modern term is headline4. This feature was deprecated after v1.13.8.. (deprecated_member_use at [flutter_login_signup] lib\src\loginPage.dart:207)
info: 'display1' is deprecated and shouldn't be used. This is the term used in the 2014 version of material design. The modern term is headline4. This feature was deprecated after v1.13.8.. (deprecated_member_use at [flutter_login_signup] lib\src\signup.dart:125)
info: 'display1' is deprecated and shouldn't be used. This is the term used in the 2014 version of material design. The modern term is headline4. This feature was deprecated after v1.13.8.. (deprecated_member_use at [flutter_login_signup] lib\src\welcomePage.dart:100)
ESTO NO IMPIDE QUE SE EJECUTE EL PROGRAMA



INSPECTOR
Para inspeccionar el codigo
1. Una ves el programa este ejecutado en la maquina/celular virtual corriendo en caliente
2. Ejecutamos el Flutter inspector que esta a la derecha de la pantalla en Android studio , alado de Flutter Outline, Flutter Performance. O puedes buscarlo y ejecutarlo desde la barra de manu.
3. Una ves que el Flutter inspector este abierto seleccionamos la opcion de Enable Select Widget Mode , esto nos permitira ver en la cascada de conjunto de codigo que representa visualmente en la maquina/celular virtual. Igualmente te lo muestra remarcandolo con un Cuadro Azul.

GIT  - Github
1. Para usar el control de versiones Github se accede a VCS > import into version control >  Git Hub (Con esto podemos validar si esta Git esta instalado en la maquina en este caso, no estaba instalado asi que mediante el link  https://git-scm.com/download
2. Despues de instalarlo debemos cerrar android studio y volverlo a abrir, para que reconosca los cambios
3. Despues verificar en le parte de Settings > Version Control > Git (Para verificar si reconoce el software git instalado en la maquina)
4. Despues de tener el codigo listo, se realiza un COMMIT en el cual adjuntamos la nueva version en pre-stage 




_________________________________________________________________
Beneficios de Flutter + Dart


Many linguists believe that the natural language a person speaks affects how they think. Does the same concept apply to computer languages? Programmers working in different kinds of programming languages often come up with radically different solutions to problems. As a more extreme example, computer scientists eliminated the goto statement to encourage more structured programs (not quite the same as totalitarian leaders in the novel 1984 expunging heretical words from natural language to eliminate thoughtcrimes, but you get the idea).

What does this have to do with Flutter and Dart? Quite a bit actually. The early Flutter team evaluated more than a dozen languages, and picked Dart because it matched the way they were building user interfaces.

Dart is a big reason why developers love Flutter. As one tweet puts it:

Here is a quick list of the Dart features that together make it indispensable for Flutter:

Dart is AOT (Ahead Of Time) compiled to fast, predictable, native code, which allows almost all of Flutter to be written in Dart. This not only makes Flutter fast, virtually everything (including all the widgets) can be customized.
Dart can also be JIT (Just In Time) compiled for exceptionally fast development cycles and game-changing workflow (including Flutter’s popular sub-second stateful hot reload).
Dart makes it easier to create smooth animations and transitions that run at 60fps. Dart can do object allocation and garbage collection without locks. And like JavaScript, Dart avoids preemptive scheduling and shared memory (and thus locks). Because Flutter apps are compiled to native code, they do not require a slow bridge between realms (e.g., JavaScript to native). They also start up much faster.
Dart allows Flutter to avoid the need for a separate declarative layout language like JSX or XML, or separate visual interface builders, because Dart’s declarative, programmatic layout is easy to read and visualize. And with all the layout in one language and in one place, it is easy for Flutter to provide advanced tooling that makes layout a snap.
Developers have found that Dart is particularly easy to learn because it has features that are familiar to users of both static and dynamic languages.

https://hackernoon.com/why-flutter-uses-dart-dd635a054ebf
https://ingenieriadesoftware.es/compilacion-ahead-of-time-vs-just-in-time/




