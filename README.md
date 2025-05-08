# Desafio 6
# Exercicio 1
```java
    int n; 
    n = 100;
    while (n >= -100) {
    System.out.println(n);
    n--;
  ```
 # Exercicio 2
```java
        int numero, soma;
        numero = 1;
        soma = 0;
        while(numero <= 20){
            if(numero %2==0){
                soma+=numero;
              
        }
        numero++;
        }
        System.out.println("soma dos numeros pares: "+soma);
    
    }
    }
```
# Exercicio 3
```java
    int n, soma;
    soma = 0; 
    n = 1;
    while ( n <= 20 ) {
    if ( n % 2 == 0) {
    soma += n;
    }
    }
    n++;
    System.out.println("Soma dos números pares: "+soma);
```
# Exercicio 4
```java
    int numero,fatorial, x; 
    Scanner ler = new Scanner(System.in); 
    fatorial = 1;
    x = 1; 
    System.out.println("Digite um número: "); 
    numero = ler.nextInt();
    if(numero<0){ 
    System.out.println("Número inválido"); 
    return; 
    } 
    do{ fatorial *= x; x++;
    } while(x<=numero); 
    System.out.println("O fatorial de " + numero + " é: " + fatorial);
```
# Exercicio 5 
```java
    int chute, nSorte; 
    Scanner ler = new Scanner(System.in); 
    nSorte = (int) (Math.random() * 100) + 1; 
    System.out.println("Tente acertar um número de 1 a 100"); 
    do { System.out.println("Digite seu chute: ");
    chute = ler.nextInt();
    if (chute < nSorte) { 
    System.out.println("Errou! Tente um número maior."); 
    } else if (chute > nSorte) {
    System.out.println("Errou! Tente um número menor.");
    } else { 
    System.out.println("Parabéns! Você acertou!");
    }
    } while (chute != nSorte);
```
# Exercicio 6
```java
    int numero, inicio, fim, x;
     Scanner ler = new Scanner(System.in);
    System.out.println("Digite o número que deseja ver a tabuada: "); 
    numero = ler.nextInt(); 
    System.out.println("Qual será o número de início da tabuada? ");
    inicio = ler.nextInt();
    System.out.println("Qual será o fim da tabuada? "); 
    fim = ler.nextInt();
    System.out.println("Tabuada do " + numero + " de " + inicio + " até " + fim); 
    for ( x = inicio; x <= fim; x++) { 
    System.out.println(numero + " x " + x + " = " + (numero * x));
```
# Exercicio 7
```java
    int soma, x; 
    soma = 0;
    for (x = 1; x <= 200; x++) { 
    if (x % 2 != 0) { 
    soma += x;
    }
    } 
    System.out.println("A soma dos números ímpares de 1 a 200 é: "+soma);
```
