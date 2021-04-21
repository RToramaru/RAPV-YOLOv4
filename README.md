# RAPV-YOLOv4

Dados de rede obtidos para a detecção de placas veiculares.

O treinamento foi realizado utilizando o sistema de detecção de objetos YOLOv4
com o framework Darknet e os dados Sense-ALPR

Para mais informacoes sobre o YOLO consulte o link: https://pjreddie.com/darknet/yolo/

Para mais informacoes sobre o Darknet consulte o link: https://github.com/pjreddie/darknet/

Para mais informacoes sobre o dataset consulte o link: http://smartsenselab.dcc.ufmg.br/dataset/banco-de-dados-sense-alpr

Os arquivos referentes as classes, descritores e pesos se sencontram em suas respectivas pastas

Os resultados obtidos são vistos na tabela

| ACURÁCIA | TPRECISÃO | REVOCAÇÃO              |    F1-SCORE               |
|--------:|----------------------------|:--------------------:|:------------------|
|   0.9344      |          0.9325                  |       0.9920               |  0.9613                 |


### O funcionamento consiste nas imagens da seguinte forma :
#### Detecção do veículo
Para a detecção do veiculo a imagem necessita ser RGB ou BGR
#### Detecção das regiões dos caractres
Para a detecção das regiões dos caracteres a imagem necessita ser da placa em escala de cinza
#### Detecção dos caracteres
Para a detecção do veiculo a imagem necessita ser apenas dos caracteres binária

### Uma representação dessas etapas podem ser vistas nas imagens

![placa](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/placa.png)

![regiao](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/regiao.png)

![O](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/O.png)
![K](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/K.png)
![K](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/K.png)
![7](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/7.png)
![4](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/4.png)
![4](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/4.png)
![8](https://github.com/RToramaru/RAPV-YOLOv4/blob/main/images/8.png)
