# console.log()

Primeiramente é necessário entender que o **console** é um objeto, e o **log()** é apenas um método deste objeto.

Há diversos outros métodos, como:

- error();
- warn();
- clear();
- time();
- table();
- count();
- group();
- e o próprio log();

Cada um tem a sua utilização específica, o **log()** tem como sua função emitir mensagens de depuração do sistema

No console (seja do editor de códigos ou do browser) todas as mensagens que estiverem dentro de console.log() serão exibidas.

Porém deveremos tomar cuidado ao escrever um texto **(string)**, pois o texto só será exibido caso esteja entre aspas ou crases **(chamamos de template string (template literals) )**, sejam duplas **(" ")** ou simples **('')**, caso contrário gerará um erro no console.

```javascript
console.log("Olá mundo!"); //String

console.log("Olá mundo!"); // String

console.log(`Olá mundo!`); // String, chamamos de Template Strings (Template Literals)

//O ";" é opcional, você pode ou não colocar ele
```

Normalmente utilizamos o console.log() para acompanhar os valores de variáveis durante a execução de algum código com o intuito de identificar algum bug ou entender como o código está se comportando.

Caso eu quisesse colocar aspas simples dentro de aspas duplas ou vice-versa, eu devo usar apenas um tipo de aspas de cada vez, por exemplo:

```javascript
console.log("Fábio 'Monsores'");

//Aqui estou usando aspas duplas fora e aspas simples dentro, o contrário também é válido.

console.log('Fábio "Monsores"');

//Aspas simples fora e aspas duplas dentro.

//Usar os dois tipos dentro de template strings também é válido:

console.log(`"Fábio" 'Monsores'`);

//Porém posso usar os dois tipos de aspas apenas dentro de template strings.`
```

Caso eu queira, eu também posso exibir números dentro de console.log(), porém números são mais fáceis de interpretar já que não necessitam de aspas ou crases, é só escrever de forma literal.

```javascript
console.log(12); //Number
console.log(12.52); //Number
```
