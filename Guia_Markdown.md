## Índice
- [Formatações básicas: itálico, negrito, riscado](#🔷formatações-básicas🔷)
- [Listas: numérica, com marcadores, de seleção](#🔷listas🔷)
- [Citações](#🔹citações🔹)
- [Títulos](#🔷títulos🔷)
- [Divisores](#🔷divisores🔷)
- [Imagens](#🔷imagens🔷)
- [Links](#🔷links🔷)
- [Escrever códigos](#🔷códigos🔷)
- [Tabelas](#🔷tabelas🔷)
- [Escrever caracteres especiais](#🔷caracteres🔷)
- [Caracteres matemáticos](#🔷caracteres-matemáticos🔷)
- [Criar índice](#🔷índice🔷)

### 🔷Formatações básicas🔷
#### 🔹Itálico🔹
```
_Itálico1_
*Itálico2*
```
_Itálico1_  
*Itálico2*  

#### 🔹Negrito🔹
```
__Negrito1__
**Negrito2**
```
__Negrito1__  
**Negrito2**  

#### 🔹Riscado (Strike)🔹
```
~~Strike~~
```
~Strike~  
#### 🔹Mistura🔹
```
_**Mistura**_
```
_**Mistura**_

*Importante:
- Não vai funcionar se você der espaço entre os símbolos e os caracteres.

---
### 🔷Listas🔷
#### 🔹Numerada🔹
```
1. um
2. dois
3. três
```
1. um
2. dois
3. três

Os números não precisam estar necessariamente em ordem, idependente do número, na formatação o markdown substituirá por 1, 2, 3 em ordem.
Exemplo: lista apenas com o número 1:
```
1. um
1. dois
1. três
```
1. um
1. dois
1. três

Usando `TAB` ou 3 espaços antes do número será criado outro nível

```
1. um
   2. dois
3. dois
  4. quatro 
```
1. um
   2. dois
3. dois
  4. quatro
#### 🔹Marcadores🔹
```
- um
- dois
- três
```
- um
- dois
- três
```
* Um
* Dois
* Três
```
* Um
* Dois
* Três
#### 🔹Tarefas🔹
```
- [ ] Tarefa 1
- [x] Tarefa 2
- [ ] Tarefa 3
```
- [ ] Tarefa 1
- [x] Tarefa 2
- [ ] Tarefa 3

#### 🔹Citações🔹
```
> Citar
>> Citar dentro da citação
>>> Citar dentro de citar dentro da citação
>>>> Assim por diante
```
> Citar
>> Citar dentro da citação
>>> Citar dentro de citar da citação
>>>> Assim por diante
____________________________________________
### 🔷Títulos🔷
```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título  6
```

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título  6
___________________________________________
### 🔷Divisores🔷
```
---
```
---
```
***
```
***
```
___
```
___

### 🔷Imagens🔷
```
![Logo do markdown]
```
### 🔷Links🔷
```
[texto com link](https://github.com/TauaneCustodio)

https://github.com/TauaneCustodio
```
[texto com link](https://github.com/TauaneCustodio)

https://github.com/TauaneCustodio
____________________________________________
### 🔷Códigos🔷
```
`Linha de código`
```
`Linha de código`
```

    ```
    Quadro de código
    ```
```
```
Quadro de código
```  
Para escrever quadros de códigos de uma linguagem específica basta colocar o nome depois do ```  
```

    ```html
    <h2> Quadro de código </h2>
    ```
```

```html
<h2> Quadro de código </h2>
```
____________________________________________
### 🔷Tabelas🔷
```
| Sem marcador | Alinhado à esquerda | Centralizado | Alinhado à direita |
|---|:---|:---:|---:|
| exemplo | exemplo | exemplo | exemplo |
```
| Sem marcador | Alinhado à esquerda | Centralizado | Alinhado à direita |
|---|:---|:---:|---:|
| exemplo | exemplo | exemplo | exemplo |

Alinhamento:  
Esquerda: `|---|:---|`  
Centro: `|:---:|`  
Direita: `|---:|`

*Colocar nas estremidades "|" é opcional 

O site [tablesgenerator](https://www.tablesgenerator.com/markdown_tables) cria para você a estrura da tabela para não ser necessário digitar todos os caracteres.
Como usar:

### 🔷Caracteres🔷

Para usar caracteres que tem alguma função:    

```
**Caractere**
\**Caractere\**
\*\*Caractere\*\*
```  

**Caractere**  
\**Caractere\**  
\*\*Caractere\*\*

Emojis
- windows + .
ou:
```
:shield:
:computer:
:hourglass:
```
:shield:  
:computer:  
:hourglass:

[Lista com vários emojis](https://github.com/ikatyang/emoji-cheat-sheet)

### 🔷Caracteres matemáticos🔷 

```
Area of a circle is $\pi r^2$

And, the area of a triangle is:

$$
A_{triangle}=\frac{1}{2}({b}\cdot{h})
$$
```

Area of a circle is $\pi r^2$

And, the area of a triangle is:

$$
A_{triangle}=\frac{1}{2}({b}\cdot{h})
$$
[Fonte](https://learn.microsoft.com/pt-br/azure/devops/project/wiki/markdown-guidance?view=azure-devops&WT.mc_id=blog-devto-ludossan)  

### 🔷Índice🔷
```
[Listas](#🔷listas🔷)
```
[Listas](#🔷listas🔷)