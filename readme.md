## PROPRIEDADES FUNDAMENTAIS:

Todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filho(s)`

---

### CONTAINER (pai)

- display: grid;
- grid-template;
  - grid-template-columns;
  - grid-template-rows;
  - grid-template-areas;
- gap;
  -row-gap;
  -column-gap;

### ITENS (filhos)

- grid-column;
  - grid-column-start;
  - grid-column-end;
- grid-row;
  - grid-row-start;
  - grid-row-end;

---

### PROPRIEDADES DE ALINHAMENTO:

Existem 9 propriedades fundamentais

**6 aplicadas em container** <br/>
`align-content` <br/>
`justify-content` <br/>
`place-content` <br/>

`align-itens` <br/>
`justify-itens` <br/>
`place-itens` <br/>

**3 aplicadas em items** <br/>
`align-self` <br/>
`justify-self` <br/>
`place-self` <br/>

Então podemos separar em 3 grupos: <br/>
`align` Y, `justify` X, `place` Y,X

E cada um deles irá observar ou o

- conteúdo do elemento `content`
- itens do elemento `items`
- o próprio elemento `self`

---

### PROPRIEDADES AUTO

- grid-auto-flow
- grid-auto-rows
- grid-auto-columns
