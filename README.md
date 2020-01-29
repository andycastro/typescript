Here we shows some things about TypeScript, concepts, theory and samples.

# TypeScript

TypeScript é um Super Set JavaScript Que adiciona tipagem estática ao JavaScript, como também outros recursos à linguagem, tornando o desenvolvimento mais próximo das linguagens tipadas/orientada a objetos.

## Prós

- Diminui os erros clássicos de linguagens não tipadas
- Força a padronização do código com a equipe de devs


## Contras

- Aumenta o tempo de desenvolvimento, por ter uma série de requisitos mínimos de tipagens para serem utilizados

## Get Started

_Install_
```npm install -g typescript```

_Compile to JS_

```tsc nameFile.ts```

_Tipos_

```
texto: string;
numero: number;
qualquer: any;
boleano: boolean;
array: Array<any>;
```

### Exemplos TS

```
class default {

  texto: string;
 
  constructor(){
    this.fn_js();
  }

  fn_js(){
    this.texto = 'Apenas um texto';
    return console.log(texto);
  }

}
```

### Exemplo transpilado para JS es5/es6

```
var default_1 = /** @class */ (function () {
    function default_1() {
    }
    return default_1;
}());
{
    texto: string;
    constructor();
    {
        this.fn_js();
    }
    fn_js();
    {
        this.texto = 'Apenas um texto';
        return console.log(texto);
    }
}

```