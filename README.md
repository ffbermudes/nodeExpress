# Express Framework
## Chamada do módulo:
````
const express = require('express');
const app = express();
````

##### Na primeira linha temos a chamada do modulo utilizando o require. Após isso vamos ativar o módulo com o método construtor `express()`. A partir de agora app será o objeto instanciado para se trabalhar com nosso __servidor__.

---

## Método GET:

````
app.get('/', (req, res) => {
  res.send('Hello World!')
})
````
##### Quando um cliente requisitar uma url correspondente ao primeiro parâmetro do método GET do nosso servidor o evento do código acima será disparado, dessa forma poderemos agora trabalhar com a resposta do mesmo.