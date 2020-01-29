Here we shows some things about TypeScript, concepts, theory and samples.

# TypeScript

TypeScript é um Super Set JavaScript Que adiciona tipagem estática ao JavaScript, como também outros recursos à linguagem, tornando o desenvolvimento mais próximo das linguagens tipadas/orientada a objetos.

## Prós

- Diminui os erros clássicos de linguagens não tipadas
- Força a padronização do código com a equipe de devs


## Contras

- Aumenta o tempo de desenvolvimento, por ter uma série de requisitos mínimos de tipagens para serem utilizados

## Get Started

--Install--
```npm install -g typescript```

--Execute--

```tsc nameFile.ts```

## Exemplos

```
class default {

  //tipos

  texto: string;
  numero: number;
  qualquer: any;
  boleano: boolean;
  array: Array<any>; 

}
```