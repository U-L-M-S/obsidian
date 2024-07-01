---
{"dg-publish":true,"permalink":"/02-resources/notes/java-condition/","tags":["java/loop"],"noteIcon":"","updated":"2024-06-21T16:36:59.686+02:00"}
---


```java
public class ConditionalOperator {
    public static void main(String[] args) {
        int a = 3, b = 5, max;
        max = (a > b) ? a : b;

        System.out.println("Der gr��te Wert ist: " + max);
    }
}
```