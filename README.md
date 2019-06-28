# Query-image
Content Based Image Retrieval with Autoencoders


# Introdução

Esse projeto tem a intenção de recriar uma versão conhecida de um buscador de imagens com o uso do Keras. Esse buscador é um exemplo de um tipo de técnica chamada [Content Based Image Retrieval](https://en.wikipedia.org/wiki/Content-based_image_retrieval). 

Para esse projeto, é planejado o uso do Keras para implementação de um [Autoencoder](https://en.wikipedia.org/wiki/Autoencoder). Autoencoders são redes neurais que tem a capacidade de ter em seu output o mesmo input que recebe. Inicialmente isso parece uma trivialidade, mas o grande trunfo da rede é a capacidade dela comprimir os dados no meio do caminho. Outros usos do Autoencoder são a construção de [sistemas de recomendação](https://medium.com/data-hackers/deep-learning-para-sistemas-de-recomenda%C3%A7%C3%A3o-parte-2-filtragem-colaborativa-com-autoencoders-347ba7d53bae). 


Nesse projeto, utilizaremos as capacidades de redução de dimensionalidade do Autoencoder e estratégias de recomendação para buscar por imagens que tenham o conteúdo parecido. Alex Krizhevsky e Geoffrey E.Hinton já proporam uma solução, como:

1.[Using Very Deep Autoencoders for Content-Based Image Retrieval](https://pdfs.semanticscholar.org/64b5/4bdf023624da4f261cdd18ac57716658e81f.pdf)


Adicionalmente, será utilizado a base de dados [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), um dataset de 60 mil imagens coloridas de 32x32 pixels. Essas imagens são formadas por 10 classes, sendo elas: 

![cifar](https://appliedmachinelearning.files.wordpress.com/2018/03/cifar2.jpg)

## Chega junto no time

É bacana ter algum conhecimento sobre Machine Learning e um pouquinho sobre a matemática por trás de Redes neurais. Se você não tiver esse conhecimento, não se sinta intimidado. Vamos estudar juntos!

Comece por aqui, será o nosso guia tbm: 

1) [DataCamp - Python Courses](https://www.datacamp.com/courses/tech:python/topic:machine_learning)
2) [Neural Networks 101 - Synaptic](https://github.com/cazala/synaptic/wiki/Neural-Networks-101)
3) [Neural Networks 101 - James le](https://medium.com/cracking-the-data-science-interview/neural-networks-101-ee21cd508499)
4) [Deep Learning — Convolutional Neural Networks Basic 101 - Judy Shih](https://medium.com/@judyshih318/deep-learning-convolutional-neural-networks-basic-101-6f32e219e78f)
5) [Short Introduction to Convolutions and Pooling: Deep Learning 101! - Packt_Pub](https://medium.com/analytics-vidhya/deep-learning-methods-1700548a3093)


# Primeiros Passos

Em breve um arquivo de `requirements` será disponibilizado. É fortemente recomendado o uso de ambientes virtuais: 

- [VirtualEnvWrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html)

Para contribuir com esse projeto, instale os pacotes iniciais:

- [Keras](https://keras.io/)

- [Scikit-learn](https://scikit-learn.org/stable/)

- [Numpy](https://www.scipy.org/scipylib/download.html)

- [Pandas](http://pandas.pydata.org/pandas-docs/stable/)

- [Jupyter Notebook](https://jupyter.org/install) - Opcional, bom para prototipar
