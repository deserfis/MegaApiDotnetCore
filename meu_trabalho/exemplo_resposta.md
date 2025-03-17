# 📌 API de Classificação de Personalidade MBTI

🚀 **Versão:** 1.0.0  
📅 **Última atualização:** Março de 2025  
🔍 **Descrição:** Esta API utiliza **Machine Learning** para prever o tipo de personalidade **MBTI** com base em respostas do usuário. Retorna os resultados em **JSON** com informações detalhadas sobre a personalidade identificada.

---

## 🛠️ Tecnologias Utilizadas

A API foi desenvolvida com as seguintes tecnologias:

| Pacote        | Versão   | Descrição | Link |
|--------------|---------|----------------|-------------------------------------------|
| **Python**   | 3.8+    | Linguagem principal | [Python](https://www.python.org/) |
| **Flask**    | 2.0     | Framework web leve | [Flask](https://flask.palletsprojects.com/) |
| **scikit-learn** | 0.24.2  | Machine Learning | [scikit-learn](https://scikit-learn.org/) |
| **Pandas**   | 1.2.3   | Manipulação de dados | [Pandas](https://pandas.pydata.org/) |
| **NumPy**    | 1.20.1  | Computação numérica | [NumPy](https://numpy.org/) |

---

## 🎯 Como Funciona?

1. O usuário envia respostas para um conjunto de perguntas.
2. A API processa os dados usando um modelo de **Machine Learning**.
3. A API retorna um **JSON** com o tipo de personalidade MBTI identificado.

---

## 📡 Endpoints da API

### 🔍 **1. Predição de Personalidade**
**`POST /predict`**  

- **Descrição:** Recebe as respostas do usuário e retorna o tipo de personalidade MBTI.  
- **Parâmetros:** JSON com as respostas do usuário.  
- **Resposta:** JSON contendo informações detalhadas sobre a personalidade.

📌 **Exemplo de Requisição:**

```json
POST /predict
Content-Type: application/json

{
  "Id": 1,
  "Name": "Alice",
  "Age": 25,
  "Answers": [
    "Eu prefiro planejar com antecedência",
    "Gosto de passar tempo sozinho",
    "Tomo decisões baseadas em lógica"
  ]
}