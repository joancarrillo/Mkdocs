# 8. Comprovació de condicions


---

<small class="small">UD02 · DAM · 2025</small>

### Diagrama de flux

``` mermaid
graph TD;
  A[Inici] --> B{Decisió}
  B -- Sí --> C[Acció]
  B -- No --> D[Altres accions]
  C --> E[Fins aquí]
  D --> E[Fins aquí]
```


### if / else
```java
if (x == 3) {
    System.out.println("Correcte");
} else {
    System.out.println("Incorrecte");
}
```

### switch
```java
switch (x) {
    case 1:
    case 2:
    case 3:
        System.out.println("Entre 1 i 3");
        break;
    case 4:
    case 5:
        System.out.println("4 o 5");
        break;
    default:
        System.out.println("Altres valors");
}
```

### Operador condicional (ternari)
```java
int x = (a == 10) ? b * 2 : a;
```
