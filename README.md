# Lista 2 de Exercícios Kotlin

## Execício 1. Diferença de números
```kotlin
fun main() {
    print("Insira um número: ")
    val n1 = readln().toInt()
    print("Insira outro número:" )
    val n2 = readln().toInt()
    
    val diferenca = n1 - n2
    print("A diferença entre os números é $diferenca")
}
```

---
## Execício 2. Nome completo
```kotlin
fun main() {
    print("Digite seu nome: ")
    val nome = readln().toString()
    print("Digite seu sobrenome:" )
    val sobrenome = readln().toString()
    
    print("Nome Completo: $nome $sobrenome")
}
```

---
## Execício 3. Operações de dois números
```kotlin
fun main() {
    println("Digite um número")
    var n1 = readln().toInt()
    println("Digite outro número")
    var n2 = readln().toInt()
    
    val soma = n1 + n2
    val sub = n1 - n2
    val multi = n1 * n2
    val div = n1 / n2
    
    println("Adição: $n1 + $n2 = $soma")
    println("Subtração: $n1 - $n2 = $sub")
    println("Multiplicação: $n1 x $n2 = $multi")
    println("Divisão: $n1 / $n2 = $div")
}
```

---
## Execício 4. Área do quadrado
```kotlin
fun main() {
    print("Insira o lado do quadrado, em cm: ")
    val lado = readln().toInt()
    val area = lado * lado
    
    print("A área do quadrado é $area cm²")
}
```

---
## Execício 5. Área do triângulo
```kotlin
fun main() {
    print("Insira a altura do triângulo: ")
    val altura = readln().toInt()
    print("Insira a base do triângulo: ")
    val base = readln().toInt()
    
    val area = base * altura / 2
    
    print("A área do triângulo é $area")
}
```

---
## Execício 6. Cáculo de IMC
```kotlin
fun main() {
    print("Digite seu peso: ")
    val peso = readln().toFloat()
    
    print("Digite sua altura: ")
    val altura = readln().toFloat()
    
    val imc = peso / (altura * altura)
    
    if (imc <= 18.5){
        print("Seu ínice de imc é: $imc, Magreza (Abaixo do Peso)")
    } else if (imc > 18.5 && imc <= 24.9) {
        print("Seu ínice de imc é: $imc, Normal (Peso esperado)")        
    } else if (imc >= 25 && imc <= 29.9) {
        print("Seu ínice de imc é: $imc, Sobrepeso (Acima do peso esperado)")
    } else {
        print("Seu ínice de imc é: $imc, Obresidade")
    }
}
```

---
## Execício 7. Idade em anos
```kotlin

```
