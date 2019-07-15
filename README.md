# CódigosPIBIT
Este repositório contém os códigos da iniciação científica cujo título correspondente é:

INOVAÇÃO TECNOLÓGICA NA GESTÃO MUNICIPAL: 
  PLATAFORMA PARA GESTÃO DE ÁREAS VERDES VIA APLICAÇÃO DE REDES NEURAIS ARTIFICIAIS EM IMAGENS

# Aqui encontram-se 3 arquivos:
  1) DCNN corresponde a rede usada para gerar o modelo.
  2) Tree_modelPErroM193leafsP190012850EPOCHS.h5 é o modelo gerado.
  3) load_model.py é um script em python para testar o modelo.
  
# Aqui encontra-se 1 pasta:
1) test onde se encontra as imagens utilizadas para testar o modelo.
  
# Para utilizar o script load_model.py:
  utilizando o ubuntu 16.04 ou versões mais recentes.
  1) instalar python 3.5.2 ou versões mais recentes
  
  2) instalar as bibliotecas tensorflow, keras, numpy, imutils e opencv
  
    para isso basta instalar o pip (pacote gerenciador do python) com o seguinte comando no terminal
    
    (para acessar o terminal no ubuntu basta apertar ctrl + alt + t).
    
    sudo apt-get install python3-numpy python3-dev python3-pip python3-wheel
    
    (instalar numpy + pip + pacote de desenvolvedor do python e suas dependencias)
    
     pip3 install keras          (instalar o pacote keras)
     
     pip3 install opencv-python  (instalar o pacote open-cv)
     
     pip3 install tensorflow     (instalar o tensorflow)
     
     pip3 install imutils        (instalar o imutils)
     
     agorora no mesmo terminal digite:
     
     python3 load_model.py --images test --model Tree_modelPErroM193leafsP190012850EPOCHS.h5
     
