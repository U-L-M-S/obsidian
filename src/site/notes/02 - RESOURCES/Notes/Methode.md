---
{"dg-publish":true,"permalink":"/02-resources/notes/methode/","tags":["OOP"],"noteIcon":"","updated":"2024-06-24T15:43:21.013+02:00"}
---

> Eine Methode ist eine Funktion, die innerhalb einer [[Klasse\|Klasse]] definiert ist und auf Instanzen dieser [[Klasse\|Klasse]] angewendet werden kann. [[02 - RESOURCES/Notes/Methode\|Methode]]n haben Zugriff auf die [[Daten\|Daten]] der Klasse und können diese manipulieren oder verwenden, um bestimmte Operationen auszuführen.


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/02-resources/notes/java-methode/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




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

</div></div>
