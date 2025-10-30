# 🏋️‍♂️ Projeto: Classe Atleta em JavaScript

Este projeto implementa uma classe `Atleta` em **JavaScript** que modela informações e cálculos relacionados a um atleta, como **IMC**, **categoria por idade** e **média válida de notas** em competições.

---

## 📘 Descrição da Classe

A classe `Atleta` possui atributos e métodos que permitem manipular e calcular dados sobre o desempenho de um atleta.

### 🔹 Atributos
- **nome**: nome do atleta
- **idade**: idade do atleta (em anos)
- **peso**: peso corporal (em kg)
- **altura**: altura (em metros)
- **notas**: array de notas atribuídas ao atleta em uma competição

### 🔹 Métodos
| Método | Descrição |
|--------|------------|
| `calculaCategoria()` | Retorna a categoria do atleta com base na idade |
| `calculaIMC()` | Calcula o IMC do atleta (`peso / altura²`) |
| `calculaMediaValida()` | Calcula a média de notas descartando a maior e a menor |
| `obtemNomeAtleta()` | Retorna o nome do atleta |
| `obtemIdadeAtleta()` | Retorna a idade do atleta |
| `obtemPesoAtleta()` | Retorna o peso do atleta |
| `obtemAlturaAtleta()` | Retorna a altura do atleta |
| `obtemNotasAtleta()` | Retorna o array de notas do atleta |
| `obtemCategoria()` | Retorna a categoria calculada |
| `obtemIMC()` | Retorna o IMC calculado |
| `obtemMediaValida()` | Retorna a média válida calculada |

---

## 💻 Exemplo de Uso

```javascript
// Instanciando um atleta
const atleta = new Atleta("Cesar Abascal", 30, 80, 1.70, [10, 9.34, 8.42, 10, 7.88]);

console.log("Nome: " + atleta.obtemNomeAtleta());
console.log("Idade: " + atleta.obtemIdadeAtleta());
console.log("Peso: " + atleta.obtemPesoAtleta());
console.log("Altura: " + atleta.obtemAlturaAtleta());
console.log("Notas: " + atleta.obtemNotasAtleta());
console.log("Categoria: " + atleta.obtemCategoria());
console.log("IMC: " + atleta.obtemIMC().toFixed(2));
console.log("Média Válida: " + atleta.obtemMediaValida().toFixed(2));
```

### 🧮 Saída esperada:
```
Nome: Cesar Abascal
Idade: 30
Peso: 80
Altura: 1.7
Notas: 10,9.34,8.42,10,7.88
Categoria: Adulto
IMC: 27.68
Média Válida: 9.25
```

---

## ⚙️ Execução

Para executar o projeto:
1. Salve o código em um arquivo chamado `atleta.js`
2. Execute com **Node.js**:
   ```bash
   node atleta.js
   ```

---

## 🧠 Conceitos Abordados

- Programação Orientada a Objetos (POO)
- Encapsulamento e Métodos de Acesso
- Cálculo de IMC
- Manipulação de arrays (ordenação, remoção e média)
- Estruturas condicionais

---

## 📝 Autor

**Rudney Rocha**  
💼 Projeto educacional para prática de JavaScript e POO.

