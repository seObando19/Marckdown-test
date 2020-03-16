<!--Headings-->

# My Title h1
## My Title h2
### My Title h3
#### My Title h4
##### My Title h5
###### My Title h6

<!--Texto en cursiva italic-->
This is an *italic* text

<!--Texto en negrita strong-->
This is a **strong** text

<!--Texto en tachado strikethrought-->
este es un ~~texto~~ tachado

<!--listas Ul desordenada-->
* apple
* orange
* etc

<!--listas Ul ordenada-->
1. apple
2. orange
3. etc

<!--Listas Ul dentro de listas-->
* Apple
    * apple 2
* Orange
    * orange 3
* Etc

1. Apple
    1. apple 2
2. Orange
3. Etc

<!--Enlaces [nombre](url sitio)-->
[faztweb.com](http://www.faztweb.com)

[faztweb.com](http://www.faztweb.com "Custom title")

<!--hacer citas-->
> This a quote

<!--linea divisora hr-->
***
___

<!--Pegar linea de  codigo como etiqueta <pre>-->
`
console.log(''Hello world)
`

<!--Pegar bloque de codigo-->

```javascript
router.get('/', (req,res) =>{
    //res.sendFile(path.join(__dirname, 'views/index.html'));
    res.render('index.html', {title : 'First website'});
});
```

```python
print('Hello world')
```

```html
<h1>Hola</h1>
```
<!--Tablas-->
|Tables       |Are            |Cool       |
| ----------- |:-------------:| ---------:|
|   col 3 is  | right-aligned |     $1600 |
|   col 2 is  | centered      |     $12   |
|   col 1 is  | are neat      |     $1    |

<!--generar imagenes internet-->
![visual studio code](https://folderit.net/itech/wp-content/uploads/2016/06/vsc-logo.png "vsc logo")

<!--generar imagenes local-->
![visual studio code local](./image/visual-studio-code-logo.png "vsc logo local")


<!--Github MARKDOWN-->
* [x] Task 1
* [] Task 2
* [] Task 3
* [x] Task 4