---
{"dg-publish":true,"permalink":"/02-resources/notes/arrays/","tags":["java/array"],"noteIcon":"","updated":"2024-06-21T16:28:48.630+02:00"}
---

> So wie die meisten Programmiersprachen fängt Java-Array bei 0 an.

```java
import java.util.*;

public class BeispielArrayZufallszahlen {

	public static void main(String[] args){
		int anzahlElemente = 20;
		int[] feld = new int[anzahlElemente];
		
		for(int i = 0; i < anzahlElemente; i++){
			feld[i] = (int)(Math.random() * 10);
			System.out.println(feld[i]);
		}
		System.out.println();
	}

}
```