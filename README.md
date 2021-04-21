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

![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/placa.png)

![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/regiao.png)

![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/O.png)
![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/K.png)
![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/K.png)
![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/7.png)
![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/4.png)
![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/4.png)
![Bilby Stampede](https://github.com/RToramaru/RAPV-YOLOv4/images/8.png)
