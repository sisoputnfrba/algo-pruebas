# A.L.GO - Pruebas preliminares y finales

Dentro de este repositorio encontraran scripts que por el momento les van a servir para ver que su TP va funcionando.

Los scripts deben estar correctamente redactados, cualquier consulta o inconveniente pueden mandarlo por el canal de telegram.

[Documento de Pruebas Preliminares](https://faq.utnso.com.ar/tp-c-comenta-pruebas)

> Los resultados seran los mismos que en la implementacion de C

Los `scripts_kernel` tienen valores default en algunas vairables de entorno:

- KERNEL_HOST => localhost
- KERNEL_PORT => 8080

Para cambiar el valor puede definir una variable en la terminal y volver a correr el script. Pueden hacerlo con algo [como](https://medium.com/@aviator2012/how-to-set-env-variables-on-our-local-terminal-63bb3165606b), `export KERNEL_HOST=192.168.1.10`.

Para correr las pruebas pueden ir dentro de la carpeta `scripts_kernel` y ejecutarlo desde consola:

```terminal
> git clone https://github.com/sisoputnfrba/algo-pruebas
> cd algo-pruebas/scripts_kernel
> ./PRUEBA_DEADLOCK.sh
```
