# Atividade Diagnóstica - Conceitos Básicos de Machine Learning

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0.0+-blue)
![Google Colab](https://img.shields.io/badge/Google_Colab-OK-yellow)

## 📌 Sobre o Projeto

Esta atividade foi desenvolvida como parte do curso **"Básico em Machine Learning"** da **Atlântico Avanti**, com o objetivo de diagnosticar o conhecimento prévio do aluno sobre os principais conceitos de aprendizado de máquina. Todas as respostas foram elaboradas de forma individual.

A atividade contém explicações e exemplos práticos sobre os seguintes tópicos:

- O que é Machine Learning
- Conjuntos de treinamento, validação e teste
- Tratamento de dados ausentes
- Matriz de confusão
- Aplicações de ML em diferentes áreas

## 📋 Questões Respondidas

1. **Definição de Machine Learning com exemplo prático**
2. **Explicação dos conjuntos de dados: treino, validação e teste**
3. **Estratégias para lidar com dados ausentes (com código em Python usando Pandas)**
4. **Uso da matriz de confusão para avaliar classificadores**
5. **Áreas de interesse para aplicação de Machine Learning (ênfase na saúde)**

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- Pandas
- Google Colab

## 💡 Exemplos de Código Utilizados

```python
import pandas as pd

df = pd.read_csv('dados_pacientes.csv')

# Verificando valores ausentes
df.isnull().sum()

# Percentual de valores ausentes
(df.isnull().mean() * 100).round(2)

# Imputação de valores ausentes
df['colesterol'] = df['colesterol'].fillna(df['colesterol'].mean())
```

## ✅ Conclusão

A atividade reforça a importância da compreensão de conceitos fundamentais em Machine Learning, não apenas na teoria, mas também na prática com ferramentas como Python e Pandas. A área da saúde foi destacada como aplicação prioritária por seu impacto direto na qualidade de vida das pessoas.

## 👩‍💻 Autora

**Stephanie Tavares dos Santos**  
🔗 [LinkedIn](https://www.linkedin.com/in/stephanie-t-santos/)  
💻 [GitHub](https://github.com/stephtavzz)  

Este projeto é de caráter educacional e faz parte do programa Atlântico Avanti.

