---
tags:
  - java/loop
dg-publish: true
links: 
reference: 
path: Notes
created: 2024-06-21 16:34
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
