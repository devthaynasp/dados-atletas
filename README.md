# 🏅 Projeto Dados dos Atletas

Este projeto foi desenvolvido em **JavaScript** como parte de um desafio de certificação. O objetivo é criar uma aplicação capaz de receber informações de atletas, calcular parâmetros importantes e exibir os resultados no console.

---

## 📌 Funcionalidades

* Cadastro de atleta utilizando **classe (POO)**
* Cálculo automático de:

  * Categoria do atleta
  * IMC (Índice de Massa Corporal)
  * Média válida das notas (descartando a maior e a menor)
* Exibição organizada das informações no console

---

## 🧠 Regras Utilizadas

### 📂 Categorias por idade

| Idade   | Categoria     |
| ------- | ------------- |
| 9 a 11  | Infantil      |
| 12 a 13 | Juvenil       |
| 14 a 15 | Intermediário |
| 16 a 30 | Adulto        |
| Outros  | Sem categoria |

### ⚖️ Cálculo do IMC

```
IMC = peso / (altura * altura)
```

### 📊 Média válida

* Remove a **maior** e a **menor** nota
* Calcula a média com as notas restantes

---

## 🧪 Exemplo de saída

```
Nome: Cesar Abascal
Idade: 30
Peso: 80
Altura: 1.7
Notas: 10,9.34,8.42,10,7.88
Categoria: Adulto
IMC: 27.68
Média válida: 9.25
```

---

## 📁 Estrutura do projeto

```
dados-atletas/
├── dados-atletas.js
└── README.md



