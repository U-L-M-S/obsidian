---
tags:
  - java/user-input
dg-publish: true
links: 
reference: 
path: Notes
created: 2024-06-21 16:29
---

```java
import java.util.Scanner;

public class BeispielEinUndAusgabe {

    public static void main(String[] args) {

        // TODO Auto-generated method stub

        Scanner input = new Scanner(System.in);

        System.out.println("Geben Sie bitte ihren Namen ein: ");

        String name = input.nextLine();

        System.out.println("Geben Sie bitte ihr Alter ein: ");

        int alter = input.nextInt();

        System.out.println("Geben Sie ihre K�rpergr��e ein: ");

        double groesse = input.nextDouble();

        System.out.println("Geben Sie ihr Gewicht ein:");

        double gewicht = input.nextDouble();

        // Ausgabe der Daten

        System.out.println("Sie heissen " + name + ", sind " + alter + " Jahre alt, sind " + groesse + " m gross und wiegen " + gewicht + " Kilogramm.");

        input.close();

    }
  
}
```
