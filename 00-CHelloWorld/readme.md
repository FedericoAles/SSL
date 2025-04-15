# Informacion del compilador

- Compilador seleccionado: GCC
- Version: 14.2.0
- Version de C que compila: hasta C2x inclusive


## Verificacion de la version de C


 Para verificar que el compilador compila hasta la version que mencione previamente hice lo siguiente:

- Abri una terminal y empece a probar diversas versiones de C mediante el comando "gcc -std=(version de c a probar) hello.c -o hello.exe" hasta llegar a la version c23, tambien conocida como C2x. 
- Como fui capaz de ejecutar "gcc -std=c23 hello.c -o hello.exe" sin problemas, y sin recibir errores, pude concluir que hasta esa version podia compilar.
