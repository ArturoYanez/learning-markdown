<!-- HEADINGS / ENCABEZADOS -->

# My title h1
## My title H2
### My title h4
#### My title H4
##### My title H5
###### My title H6

___

<!-- TEXT FORMAT / FORMATO DE TEXTO -->
<!-- Italic Text -->
This is an *Italic* Text

<!-- Strong Text -->
This is an **Strong** Text

<!-- Strikethrough Text -->
This is an ~~Strikethrough~~ Text

___

<!-- LIST / LISTAS -->
<!-- Unorder List -->
* Apple
    * Apple Two
* Orange
* Pinneaple

<!-- Order List -->
1. Apple
    1. Apple Two
2. Orange
3. Pinneaple

___

<!-- LINK / ENLACES -->
<!-- Simple Link -->
[Faztweb.com](https://www.faztweb.com)

<!-- Link with Custom Title -->
[Faztweb.com](https://www.faztweb.com "Custom title")

___

<!-- QUOTES / CITAS -->
> This is a Quote
___

<!-- DIVISOR LINE / LINEA DIVISORIA / <HR> -->
<!-- Thick Line -->
---

<!-- Fine Line -->
___

___

<!-- CODE BOX / CAJA DE CÓDIGO -->
<!-- Code Line / Linea de Código -->
`console.log("Hola mundo")`

<!-- Code Block / Bloque de Código -->
```
for (var i = 2; i < num; i++) {

        console.log(`El módulo entre ${num} y ${i} es = ${num % i}`);

        if (num % i === 0) {
            console.log(`${i} es un multiplo de ${num}`);
            console.log(`Por lo tanto ${num} no es un número primo`);
            return false;
        }
    }
```

<!-- JavaScript Example Highlighting -->
```javascript
for (var i = 2; i < num; i++) {
    
    console.log(`El módulo entre ${num} y ${i} es = ${num % i}`);
    
    if (num % i === 0) {
        console.log(`${i} es un multiplo de ${num}`);
        console.log(`Por lo tanto ${num} no es un número primo`);
        return false;
        }
    }
```

<!-- Python Example Highlighting -->
```python
print("Hello World")
```

<!-- HTML Example Highlighting -->
```html
<h1> Hello World</h1>
```
___

<!-- TABLES / TABLAS -->

| Tables        | Are           | Cool  |
| ------------- |:-------------:|:-----:|
| col 3 is      | right-aligned | $1600 |
| col 2 ix      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

___
<!-- IMAGES / IMÁGENES -->

<!-- Embed Image / Imágen Embedida -->
![visual studio code logo](https://i.pinimg.com/originals/00/f4/05/00f40564d281eee8dbb931024b8e6975.png "vscode logo")

<!-- Local Image / Imágen Local -->
![visual studio code logo](img/00f40564d281eee8dbb931024b8e6975.png "vscode logo")

___
<!-- GITHUB MARKDOWN -->

* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [x] Task 4
