# ejercicio1_branch

## Se copia el repositorio

```code
git clone https://github.com/diego-febles-seoane/ejercicio1_branch
Clonando en 'ejercicio1_branch'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.
```

## Se crea la rama

```code
git checkout -b ejercicio1-branch
Cambiado a nueva rama 'ejercicio1-branch'
```

## Se crea el .java

```code
     public class Ejercicio1 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }    
```

## Se realiza el commit

```code
git commit -m "Se incluye el Ejercicio1.java"
[main 9d5fc7d] Se incluye el Ejercicio1.java
 2 files changed, 36 insertions(+), 1 deletion(-)
 create mode 100644 Ejercicio1.java
 rewrite README.md (100%)
 ```

 # ejercicio2_branch

 ## Se crea la rama

```code
git checkout -b ejercicio2-branch
Cambiado a nueva rama 'ejercicio2-branch'
```

## Se crea el .java

```code
     public class Ejercicio2 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }    
```

## Se realiza el push

```code
git push origin ejercicio2-branch
Total 0 (delta 0), reusados 0 (delta 0), pack-reusados 0
remote: 
remote: Create a pull request for 'ejercicio2-branch' on GitHub by visiting:
remote:      https://github.com/diego-febles-seoane/ejercicio1_branch/pull/new/ejercicio2-branch
remote: 
To https://github.com/diego-febles-seoane/ejercicio1_branch
 * [new branch]      ejercicio2-branch -> ejercicio2-branch
```