# Detecção e reconhecimento de animais utilizando o YOLO e Darknet

Projeto orientado à computação da 🏫 Universidade Federal de Viçosa - Campus Florestal. 

A expansão imobiliária provoca a ocupação de regiões próximas às áreas rurais, onde é comum a presença de animais próximos à presença do homem. Estes animais podem perturbar a ordem, causando transtornos, danos ou prejuízos, e até mesmo colocando em risco a segurança das pessoas. Neste projeto, foi desenvolvido um modelo de visão computacional com o objetivo de identificar a presença destes animais em imagens de vídeos de segurança, seja para simples controle de presença, monitoramento e até mesmo alarme de perigo. O modelo foi desenvolvido usando o conjunto de imagens obtidas do Open Images Dataset e treinado através do framework Darknet, obtendo resultados validados pela métrica mAP (mean Average Precision)  com  precisão media geral de 84.58% em prever e detectar os objetos das seguintes classes: Cavalo, Pessoa, Gado, Porco, Gato, Cachorro, Onça e Cobra.

## 💻 Resultados 


A função mAP, disponibilizada pelo framework Darknet, informa os seguintes valores: o número de instâncias previstas corretamente (TP), o número de instâncias previstas incorretamente (FP) e o número de instâncias que deixaram de ser previstas (FN). Através destas quantificações, a função reporta a acurácia, a revogação, a precisão e o F1-score como medida de desempenho para o nosso modelo.

Utilizando 1791 instâncias das classes de teste, o modelo obteve uma média geral de 84.58\% de acurácia (mAP) para um IoU de 0.5 e um limiar de corte threshold de 0.25 de certeza da classe obtida. Os resultados, por classe, podem ser observados na tabela:

Classe | AP | TP | FP 
--- | --- | --- | ---
Cavalo | 78.75 | 149 | 34 
Pessoa | 48.34 | 211 | 83 
Gado | 82.80 | 170 | 60 
Porco | 91.74 | 130 | 4 
Gato | 93.80 | 195 | 20 
Cachorro | 93.05 | 208 | 23  
Onca | 91.76 | 69 | 2 
Cobra | 96.39 | 156 | 4 



********************************************


## 🚀 Começando

Para obter uma cópia deste projeto:

```shell
git clone https://github.com/adrianomqsmts/animal-detection-yolo
cd animal-detection-yolo
```

## 🛠️ Construído com

Ferramentas, linguagens e outras tecnologias usadas no desenvolvimento deste sistema.


* [Google Colab](https://colab.research.google.com/) - Ambiente de Desenvolvimento
* [Python3](https://docs.python.org/3/) - Linguagem de Programação
* [YOLO](https://pjreddie.com/darknet/yolo/) - Arquitetura da rede
* [Darknet](https://pjreddie.com/darknet/) - Framework de Desenvolvimento

* ...

## ✒️ Autores

* **Desenvolvedor** - *Código e Documentação* - [Adriano](https://github.com/adrianomqsmts)


## 📄 Licença

Este projeto está sob a licença MIT License - veja o arquivo [LICENSE.md](https://github.com/adrianomqsmts/animal-detection-yolo/blob/master/LICENSE) para detalhes.

---
