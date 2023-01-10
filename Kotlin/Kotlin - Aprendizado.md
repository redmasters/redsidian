### Links: 
https://www.youtube.com/watch?v=iNCJfI48cKQ

```Kotlin
// Variavel somente leitura
val dogName = "Litinho" 

// Variavel dinamica
var nameOfDog = "Lito" 
```

```Kotlin
fun nameFun(){
	//code
}

fun nameFun(name: String){
	//code
}

fun nameFun(names: String): String{
	//code
}
```

```Java
Dog dog = new Dog();
```

```Kotlin
val dog = Dog()
```


Porque da interrogacao apos o tipo:
ex: String? 
A interrogacao apos o tipo de dado tem haver com a *feature* **Null Safety**, como descrito [neste post](https://sebhastian.com/kotlin-question-mark/) 

Em uma classe Kotlin pode se escrever o construtor logo apos o titulo da mesma:
```Kotlin 
class Dog constructor(ownerName: String){
	val name: String? = null
}
```