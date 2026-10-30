# Introdução ao TensorFlow

Repositório de estudos com laboratórios e exercícios do curso [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning](https://www.coursera.org/learn/introduction-tensorflow/), disponível na Coursera. O conteúdo acompanha a progressão do curso, da regressão simples à classificação de imagens com redes convolucionais.

## Conteúdo

| Semana | Tópicos | Materiais |
| --- | --- | --- |
| 1 | Redes neurais básicas e previsão de preços de casas | [Hello World](week01/w1_lab1.ipynb) · [Previsão de casas](week01/w1_lab2.ipynb) · [Exercício de regressão](week01/w1_assignment.ipynb) |
| 2 | Classificação de imagens com Fashion MNIST e MNIST | [Fashion MNIST](week02/w2_lab1.ipynb) · [Reconhecimento de dígitos](week02/w2_lab2.ipynb) · [Exercício com MNIST](week02/w2_assignment.ipynb) |
| 3 | Redes convolucionais, filtros e pooling | [CNN com Fashion MNIST](week03/w3_lab1.ipynb) · [Melhor modelo](week03/w3_lab2.ipynb) · [Experimento com filtros](week03/w3_lab3.ipynb) · [Exercício com CNN](week03/w3_assignment.ipynb) |
| 4 | Classificação de imagens do mundo real e visualização de camadas | [Imagens reais](week04/w4_lab1.ipynb) · [Modelo e ativações](week04/w4_lab2.ipynb) · [Exercício feliz/triste](week04/w4_assignment.ipynb) |

## Organização

```text
.
├── week01/                 # Redes neurais básicas e regressão
├── week02/                 # Classificação de imagens
├── week03/                 # CNNs, filtros e pooling
│   └── kernel-filters/     # Imagens usadas no experimento de filtros
├── week04/                 # Imagens reais e visualização de camadas
├── LICENSE
└── README.md
```

Os arquivos `*_lab*.ipynb` são laboratórios guiados; `*_assignment.ipynb` contém exercícios. Os nomes usam o prefixo `w<semana>` e identificam o tipo de material, com laboratórios numerados (`lab1`, `lab2` etc.).

## Como usar

O GitHub exibe uma prévia dos notebooks. Para executar as células, abra o arquivo no Jupyter Notebook/JupyterLab ou no Google Colab e rode-as na ordem apresentada. É necessário ter Python 3 e TensorFlow; alguns notebooks também usam bibliotecas como NumPy, Matplotlib, SciPy ou OpenCV. As células indicam quando os dados são baixados ou quando há recursos específicos do Colab.

Os resultados salvos nos notebooks foram mantidos para que as prévias incluam gráficos e exemplos. Os checkpoints do Jupyter, ambientes virtuais e arquivos locais de configuração ficam fora do versionamento conforme o `.gitignore`.

## Clonar o repositório

```bash
git clone https://github.com/Alyssonmach/introduction-to-tensorflow.git
cd introduction-to-tensorflow
```
