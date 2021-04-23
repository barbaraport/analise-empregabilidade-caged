# Como configurar o ambiente de desenvolvimento :computer:
Para desenvolver o projeto, realize os seguintes passos:

## 1. Linguagem de programação 	:abcd::symbols:
A linguagem de programação que será utilizada é o Python. Para utilizá-lo precisamos instalá-lo no computador. O download da última versão estável pode ser feito a partir [daqui](https://www.python.org/downloads/). Quando for instalar, selecione a opção **Add Python 3.9.4 to PATH** (a versão do Python é um exemplo).

## 2. Bibliotecas :books:
Após instalar o Python é necessário instalar as bibliotecas para que o projeto possa ter suas funcionalidades. Na pasta *requirements*, há um arquivo com todas as bibliotecas necessárias, chamado *requirements.txt*. Abra o **Prompt de Comando** e vá até essa pasta. Quando conseguir, copie e cole esse comando e aperte *Enter* para executá-lo:
```python
pip install -r requirements.txt
```

## 3. Hora de executar! :runner:
Volte para o diretório raiz do nosso projeto. Agora, digite no seu **Prompt de Comando** o comando:
```python
jupyter notebook
```
Seu navegador padrão abrirá e um arquivo de extensão `.ipynb` estará aparecendo. Clique nele para começar a desenvolver.