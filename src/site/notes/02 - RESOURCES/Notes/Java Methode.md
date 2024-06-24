---
{"dg-publish":true,"permalink":"/02-resources/notes/java-methode/","tags":["java/method"],"noteIcon":"","updated":"2024-06-24T16:35:26.236+02:00"}
---

## Java Methoden 

>Syntax
>accessModifier returnDateType methodName (parameters) throws exceptionList

```java
public class AwesomeJavaProgram{
// A method that throws a `NullPointerException` if the object is null
	public void printName(String name) throws NullPointerException {
		if (name == null) {
		    throw new NullPointerException("The name cannot be empty");
		}
		System.out.println(name);
	}
}
```