# Laboratório de Classificação Visual com Teachable Machine

Este repositório contém o desenvolvimento de um modelo de aprendizado de máquina para classificação visual, criado como parte de uma atividade de laboratório utilizando a ferramenta **Google Teachable Machine**.

## 📌 Sobre o Projeto

O objetivo deste laboratório foi treinar um modelo de visão computacional capaz de distinguir entre duas categorias de imagens de forma automatizada. Com base na estrutura configurada, o modelo analisa características visuais e tenta prever a qual grupo uma nova imagem pertence.

A interface do experimento foi estruturada da seguinte forma:
* **Classe 1 ("Ia"):** Conjunto de 20 amostras de imagens (provavelmente geradas por Inteligência Artificial ou de um estilo específico).
* **Classe 2 ("Real"):** Conjunto de 20 amostras de imagens de controle (obras de arte ou fotografias reais).

---

## 🛠️ Tecnologias Utilizadas

* **[Google Teachable Machine](https://teachablemachine.withgoogle.com/)**: Plataforma web intuitiva para criação de modelos de Machine Learning rápidos e acessíveis.
* **Dataset:** Imagens selecionadas e carregadas manualmente para compor os dados de treino de cada classe.

---

## 🚀 Como o Modelo Foi Construído

O fluxo de trabalho seguiu as três etapas principais da plataforma:

### 1. Coleta de Dados (Dataset)
Foram criadas duas classes distintas com 20 amostras de imagem cada:
* **Classe "Ia"**: Upload de imagens via arquivos locais.
* **Classe "Real"**: Upload de imagens via arquivos locais.

### 2. Treinamento (Training)
Com as imagens organizadas, o modelo foi processado utilizando a configuração padrão de treinamento da ferramenta, cruzando os padrões visuais para aprender a diferenciar a assinatura estética de cada classe.

### 3. Visualização e Teste (Preview)
Para testar a eficácia do modelo, foi feito o upload da famosa obra *O Grito*, de Edvard Munch, como imagem de teste na aba de **Preview**. 

**Resultado do Teste em Tempo Real:**
* **Class 1 (Ia):** ~76% de confiança.
* **Class 2 (Real):** ~24% de confiança.

> 💡 *Nota de análise:* Curiosamente, o modelo classificou a obra clássica com maior tendência para a classe "Ia", o que abre margem para discussões interessantes sobre como traços expressionistas fortes ou distorções fluidas podem se assemelhar a padrões de imagens geradas artificialmente no entendimento atual do modelo.

---

## 📦 Como Reutilizar ou Exportar

Caso queira replicar ou dar continuidade a este laboratório:
1. Acesse o [Teachable Machine](https://teachablemachine.withgoogle.com/).
2. Escolha o projeto de **Imagem**.
3. Você pode exportar o modelo treinado clicando no botão **"Export Model"** para utilizá-lo em aplicações reais via JavaScript (TensorFlow.js), Python ou até mesmo como uma API estruturada.

