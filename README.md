# metodos-
1-
```
package ex01;


public class Ex01 {

   
     
        public static void tabuada() {
int numero = ;
System.out.println(numero * 1);
System.out.println(numero * 2);
System.out.println(numero * 3);
System.out.println(numero * 4);
System.out.println(numero * 5);
System.out.println(numero * 6);
System.out.println(numero * 7);
System.out.println(numero * 8);
System.out.println(numero * 9);
System.out.println(numero * 10);
}
public static void main(String[] args) {
tabuada();
}
}
```
##

2-package ex02;

```
import java.util.Arrays;
import java.util.Scanner;

public class Ex02 {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

       
        System.out.print("Digite o primeiro número inteiro: ");
        int n1 = scanner.nextInt();

        System.out.print("Digite o segundo número inteiro: ");
        int n2 = scanner.nextInt();

       
        if (n1 > n2) {
            System.out.println("O maior número é: " + n1);
        } else if (n2 > n1) {
            System.out.println("O maior número é: " + n2);
        } else {
            System.out.println("Os dois números são iguais.");
        }

        scanner.close();
    }
}
```
##