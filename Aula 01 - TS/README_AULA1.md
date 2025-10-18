# Aula 01 – Introdução ao TypeScript

## 📌 Conteúdo Revisado
1. **O que é o TS?**  
2. **Diferença entre JS e TS?**  
3. **Iniciação e configuração**  
4. **Tipos de Dados**  
5. **Tipando variáveis e funções.**  
6. **Inferência de tipos.**
7. **Introdução a Listas**

---

## 🔹 O que é o TS?
O TS é um superset do JS, criado em 2012 pela microsoft para tornar o JS tipado e mais focado em orientação a objetos, tornando o JavaScript mais seguro.

## 🔹 Diferença entre TS e JS!

<img width="917" height="297" alt="image" src="https://github.com/user-attachments/assets/7b7da68d-f879-4ab5-be6a-05080bebd40f" />


## 🔹 Iniciando e configuração:
## Requisitos:
1. Instalar o node.js: https://nodejs.org/pt
2. Instalar o VS Code: https://code.visualstudio.com/
3. TypeScript: https://www.typescriptlang.org/
--- 
Configuração:
1. npm install -g typescript para instalar o TypeScript de forma global
2. tsc nomeDoArquivo.ts para compilar o arquivo para JS.
3. tsc --init para criar o tsconfig.json.
4. tsc --w para atualizar automaticamente.
## Arquivo tsconfig.json:
1. rootdir -> nome da pasta para colocar o arquivo TS.
2. outDir -> nome da pasta para  onde vão os arquivos JS transpilados.
3. removeComments: true -> para remover os comentários do arquivo TS.
4. module -> esnext -> Tipo de modularização. (esnext é a versão mais atualizada do ES)
5. target -> esnext -> escolher qual a versão do JS que iremos transpilar o arquivo para JS.


➡️ ## Tipos de dados:

```javascript
STRING
BOOLEAN
NUMBER
NULL
UNDEFINED
ANY- > TIPO ''CORINGA'' DO TYPESCRIPT.
```

➡️ ## Tipando variáveis e funções.  

```javascript
let age: Number = 5;

const firstName: string = "Felipe";

const isValid: boolean = true;

const productId: number | string = "1" -> intersections, um tipo OU outro!
const listasIds: number[] = [1, 2, 3, 4, 5]
```

```javascript

function multiplicarNumero(n1: number): number{
    return n1 * 2 }

//funções void são funções que não retornam nada.
const log = (message: string): void => {
  console.log(message);
};

```



---

## 📚 Dicas de Aprendizado
- Explore e teste livremente seu código.  
- Pergunte “por quê?” para entender a lógica.  
- Revise e ensine a alguém (ótima forma de aprender).  
- Pratique! Quanto mais exercícios, mais natural será programar.  

---

## 🚀 Próxima Aula (Aula 02)
- **Listas e Tuplas** → estruturas para armazenar múltiplos valores.  
Exemplo:
```javascript
lista_de_numeros: number[] = [1, 2, 3, 4, 5]
lista_de_letras: string[] = ['a', 'b', 'c']
lista_de_booleanos: boolean[] = [True, False, True]
```
