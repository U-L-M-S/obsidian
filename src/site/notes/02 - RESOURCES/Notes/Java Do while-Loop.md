---
{"dg-publish":true,"permalink":"/02-resources/notes/java-do-while-loop/","tags":["java/loop"],"noteIcon":"","updated":"2024-06-21T16:35:25.586+02:00"}
---


```java
public class Main {
    public static void main(String[] args) {
        boolean condition = true;
        int counter = 0;

        do {
            System.out.println("Die Schleife läuft: " + counter);
            counter++;
            if (counter >= 5) {
                condition = false; // Schleife beenden, wenn counter >= 5
            }
        } while (condition);
    }
}
```
