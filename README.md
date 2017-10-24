# LSTM for next word prediction problem

## Objective:
#### To learn LSTM model and apply it to solve next word prediction probem
 
## Created by:
#### P. Volkovich, M. Voronina, A. Korotkich, A. Kirisova

## Presentation:
https://docs.google.com/presentation/d/1-F77jEhWmQrOF5X9-jVFx30pFpd6X5OC0nH3esF_CWs/edit#slide=id.g25952b9b11_0_603

## References:

1) https://habrahabr.ru/company/wunderfund/blog/331310/
2) https://medium.com/towards-data-science/lstm-by-example-using-tensorflow-feb0c1968537
3) http://www.deeplearningbook.org/
4) http://colah.github.io/posts/2015-08-Understanding-LSTMs/

## How to reproduce:
1) Install Docker from https://www.docker.com 
2) Pull Tensorflow Docker image:
    $ docker pull tensorflow/tensorflow
3) Run container:
    $ docker run -it -p 8888:8888 tensorflow/tensorflow
4) Download src folder from the repository and copy it to container
5) Run: python rnn_words.py
