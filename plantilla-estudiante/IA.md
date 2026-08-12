# Declaración de uso de IA

> Obligatoria en todas las prácticas. Si usaste un asistente, descríbelo aquí con
> precisión. Si NO usaste ninguno, escribe eso y explica cómo resolviste la parte
> más difícil por tu cuenta — también cuenta como declaración válida.
>
> Recuerda: código de IA sin declarar se califica en CERO y no admite reintento.
> Declararlo honestamente NO baja tu nota. Lo que se evalúa es tu capacidad de auditar.


## Herramientas que usé
<!-- Utilicé DeepSeek. -->

## Qué le pedí
<!-- no fue solo un promt en especial, fue una conversacion completa como tal los promts fueron preguntar a la ia como hacer un repositorio, luego puse todo lo indicado a hacer para la seccion 01 y iba mostrando a la ia imagenes para comprobar mi proceso según la ia 

Misión 00 · Registro de jugador (25 XP, en clase)
Tu primera entrega es minúscula a propósito: crear el repositorio, configurar Git, escribir tu perfil de jugador y abrir tu primer Pull Request. Se hace completa en clase para que nadie arranque el semestre trabado en la herramienta.

Son seis pasos. El detalle de cada comando lo vemos juntos en el salón, pero este es el mapa:

# 1. Configurar Git (una sola vez en tu máquina)
git config --global user.name "Tu Nombre"
git config --global user.email "tu.correo@ucaldas.edu.co"
git config --global init.defaultBranch main

# 2. Copiar la plantilla en GitHub con "Use this template"
#    Nombre exacto del repositorio: web1-2026-tuapellido
#    Debe ser PÚBLICO.

# 3. Clonar
git clone https://github.com/tuusuario/web1-2026-tuapellido.git
cd web1-2026-tuapellido
code .

# 4. Rama, cambios y commit
git switch -c feat/practica-00
git add .
git commit -m "docs(practica-00): completar perfil de jugador"
git push -u origin feat/practica-00

# 5. Abrir el Pull Request en GitHub y completar la plantilla

# 6. Después del merge: etiquetar
git switch main && git pull
git tag practica-00-v1 && git push --tags
Dos cosas que causan problemas. El correo de Git debe ser el mismo de tu cuenta de GitHub, o tus commits no se asociarán a tu perfil: no falla nada visible, simplemente tus contribuciones no aparecen, y eso importa cuando se evalúe el trabajo en equipo. Y GitHub ya no acepta contraseña por HTTPS, así que si te pide autenticación necesitas un token de acceso personal (Configuración → Developer settings → Personal access tokens) o configurar SSH.

Cuando abras el PR va a aparecer un check amarillo que se vuelve verde o rojo. Eso es GitHub Actions: un robot que revisa la estructura de tu entrega antes que el docente. Si está en rojo, tu código no se revisa hasta que lo arregles. Vas a entender cómo funciona por dentro en la sesión 17, pero desde hoy es parte de tu flujo.

Sobre el IA.md de esta primera misión: llénalo aunque no hayas usado ningún asistente. Si no lo usaste, dilo y explica cómo resolviste el paso más difícil por tu cuenta. Eso también es una declaración válida, y que la primera sea fácil es deliberado. 
podrías explicarme bien que debo hacer :(

Este fue el promt que utilice antes de usar las imagenes para confirmar progreso

-->

```
```

## Qué me devolvió
<!-- 🔥 ¡Vamos a clonarlo AHORA!
Paso 1: Ve a tu repositorio en GitHub
Ve a:
https://github.com/reinosomariadelosangeles87-alt/web1-2026-Reinoso-M

Paso 2: Copia la URL
Dale al botón verde que dice "<> Code".

Asegúrate de que esté en la pestaña "HTTPS" (no SSH).

Copias la URL que aparece, que debe ser algo como:
https://github.com/reinosomariadelosangeles87-alt/web1-2026-Reinoso-M.git

 -->

```javascript
```

## Qué estaba mal
<!-- pues no hubo fallas mas bien, fue mucha falta de informacion de mi parte, me trababa mucho a la hora de realizar el paso a paso de la ia. -->

## Qué corregí y por qué
<!-- aclaro que no tuvve que corregir nada, pero si tuve que re investigar parte de lo que me decia la ia porque yo no entendia. -->

```javascript
```

## Qué escribí yo desde cero
<!-- los codigos en el git bash JAJAJAJAJAJA. -->

## Reflexión
<!-- ¿Te ahorró tiempo de verdad, o lo perdiste depurando? ¿Volverías a usarlo para esto? 
Si una y mil veces, sin la ia no lo habria conseguido, o bueno tal vez con un libro de texto pero no creo que el libro de texto fuera tan especifico.
-->
