---
{"dg-publish":true,"permalink":"/02-resources/notes/java-bsp/","tags":["java","algorithmus"],"noteIcon":"","updated":"2024-06-21T16:26:46.000+02:00"}
---


```Java
class Collatz {
    public static void main(String[] args) {
	    int user_input = 3;
	    int counter = 0;
	    while(counter < 15){
			if(user_input % 2 == 1){
				user_input = user_input * 3 + 1;  
			}
			else{
				user_input = user_input / 2;
			}
			System.out.println("Wert: " + user_input);
			counter++;
	    }
    }
}
```