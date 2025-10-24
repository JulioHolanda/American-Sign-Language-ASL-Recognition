# American Sign Language (ASL) Recognition

Este projeto utiliza redes neurais convolucionais (CNNs) — incluindo o modelo VGG16 — para realizar o reconhecimento de sinais do alfabeto ASL a partir de imagens. O notebook está baseado no dataset **ASL Alphabet** disponível no Kaggle.

## 📁 Estrutura do Projeto

```
Deep_e_IA_-_Mini-projeto_1_-_ASL.ipynb
```

## 📦 Requisitos

Antes de tudo, certifique-se de ter o Python 3.7+ instalado. Recomendamos o uso de um ambiente virtual.

Instale as dependências com:

```bash
pip install tensorflow keras matplotlib seaborn opencv-python imutils scikit-learn kagglehub
```

## 📥 Download do Dataset

Este projeto utiliza o dataset **ASL Alphabet** hospedado no Kaggle. Para baixá-lo:

1. Crie uma conta no [Kaggle](https://www.kaggle.com/)
2. Vá para [https://www.kaggle.com/datasets/grassknoted/asl-alphabet](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
3. O download é feito automaticamente pelo código usando:

```python
import kagglehub
grassknoted_asl_alphabet_path = kagglehub.dataset_download('grassknoted/asl-alphabet')
```

## ▶️ Como Executar

1. Abra o notebook:

```bash
jupyter notebook Deep_e_IA_-_Mini-projeto_1_-_ASL.ipynb
```

2. Execute as células em ordem. O processo inclui:

- Download e preparação dos dados
- Visualização de exemplos
- Treinamento do modelo CNN (VGG16, entre outros)
- Avaliação de métricas

⚠️ O tempo de execução pode variar dependendo da sua GPU/CPU.

## 📊 Resultados

Os principais resultados incluem:

- Acurácia de classificação por letra
- Matriz de confusão
- Visualizações das ativações usando Grad-CAM

## 🧠 Modelos Usados

- VGG16 com fine-tuning
- Camadas Dense customizadas
- Técnicas de Dropout

## 📌 Observações

- Idealmente executado em ambiente com GPU (ex: Google Colab)

## 🧐 Informações adicionais
### Equipe:
- Roberto Arruda: @rob-a-b  
- Julio Holanda: @JulioHolanda  
- Nicole Victory: @NicoleVictory  

## 📝 Licença
Este projeto está sob a licença MIT.
