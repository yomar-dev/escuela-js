# Escuela de JS #


### setTimeout ###

Establece un temporizador que ejecuta una función o una porción de código después de que transcurre un tiempo.

***Ejemplo***

~~~
<script>
	/**
	 * Vamos a utilizar una Arrow Function para este ejemplo.
	 */
	setTimeout(() => {
		/**
		 * Mostrar un mensaje de alerta: Han pasado 4 segundos!!
		 */
		alert('Han pasado 4 segundos!!')
	}, 4000)
</script>
~~~


### setInterval ###

Ejecuta una función o un fragmento de código de forma repetitiva cada que termina el periodo de tiempo determinado.

***Ejemplo***

~~~
<h1 id="mensaje">Han transcurrido 0 segudos!!</h1>
<script>
	let mensaje = document.getElementById('mensaje')
	let contador = 0
	/**
	 * Vamos a utilizar una Arrow Function para este ejemplo.
	 */
	setInterval(() => {
	  contador += 2
	  mensaje.textContent = `Han transcurrido ${contador} segundos!!`
	}, 2000)
</script>
~~~


### Enlaces de interes ###

[setTimeout - MDN](https://developer.mozilla.org/es/docs/Web/API/WindowTimers/setTimeout) <br>
[setInterval - MDN](https://developer.mozilla.org/es/docs/Web/API/WindowTimers/setInterval) <br>