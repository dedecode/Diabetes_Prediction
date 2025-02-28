# 📊 Predição de Diabetes  

Este repositório contém um projeto desenvolvido para a disciplina de **Inteligência Artificial**, no qual exploramos a predição de diabetes com base em características clínicas e hábitos de vida dos pacientes.  

O projeto foi realizado em dupla e tem como objetivo **demonstrar a aplicação de técnicas de aprendizado de máquina**, desde a análise exploratória dos dados até a implementação de um modelo de classificação.  

## 🔬 Base de Dados  

Os dados utilizados no projeto foram obtidos de uma fonte pública no **Kaggle**:  
🔗 [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)  

Antes da modelagem, realizamos um processo de limpeza e preparação para melhorar a qualidade dos dados, incluindo:  

- **Remoção de duplicatas**  
- **Codificação de variáveis categóricas** (`gender` e `smoking_history`)  
- **Remoção da categoria "No Info" do histórico de tabagismo** (>35% dos dados)  
- **Balanceamento da variável alvo (`diabetes`)** usando undersampling  
- **Escalonamento das variáveis numéricas** com `StandardScaler`  

## 🧠 Modelagem  

Testamos cinco modelos de aprendizado de máquina e avaliamos seu desempenho com métricas de classificação. O modelo com melhor desempenho foi a **Rede Neural MLP**, que foi salvo e disponibilizado para predição com entradas personalizadas.  

## 🎯 Teste a predição com entradas próprias  

É possível realizar uma predição personalizada utilizando nosso modelo treinado!  

📌 Basta acessar o **Google Colab** através do link abaixo e inserir seus próprios valores:  
           É necessário estar logado em uma conta Google!


🔗 **[Executar Predição no Google Colab](https://colab.research.google.com/github/dedecode/Diabetes_Prediction/blob/main/Projeto_IA_Predi%C3%A7%C3%A3o_de_Diabetes.ipynb)**  

### ⚙️ Como executar corretamente  

Para que o modelo funcione corretamente, **é necessário rodar todas as células de código antes de chegar na Seção 6** (onde é possível inserir os dados para a predição).  

👨‍💻 **Passos:**  
1. Clique no link acima para abrir o Colab.  
2. No menu superior, vá em **Executar → Executar tudo** ou rode célula por célula manualmente.  
3. Após rodar todas as etapas do pré-processamento e modelagem, vá até a **Seção 6** e insira seus próprios valores para testar a predição.  

⚠ **Importante:** Este projeto tem fins **exclusivamente educacionais** e não deve ser utilizado para diagnósticos médicos. Para qualquer avaliação clínica, consulte um profissional de saúde.  
