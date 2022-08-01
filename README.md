# U-Net-Cervical-cells-ISBI2014-
U-Net em keras Tensorflow para segmentação de células cervicais - base ISBI2014

Para execução:
  1)  Descompacte a pasta dataset.zip em uma pasta gdrive com nome 'dataset'
      - Dados de treinamento estarão em 'dataset/trainX' (imagens) e 'dataset/trainY' (máscaras)
      - Conjunto de validação em dataset/valX (imagens) e dataset/valY(máscaras)
      - os arquivos 'trainISBNI2014.csv' e 'valISBNI2014.csv' associam arquivos de imagem e máscara correspondentes
  2)  Abra o notebook 'DanielaCostaTerra_Seg_ISBI2014.ipynb' e altere CURRENT_PATH para a pasta raiz de 'dataset'
  
TODO's:
1) Saída da rede com 2 canais
2) Pipeline especializado
 
  
