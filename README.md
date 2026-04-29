# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# AI4Success — Detecção e Classificação de Objetos

## Grupo AI4Success - Turma 1TIAOR

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/durval-dorta-junior-585311202/">Durval de Oliveira Dorta Junior - RM567007</a>
- <a href="https://www.linkedin.com/">Murilo Ferreira Borges - RM567738</a>
- <a href="https://www.linkedin.com/">Guilherme Cury - RM564011</a> 
- <a href="https://www.linkedin.com/">Guilherme da Nobrega Gontijo - RM562211</a> 
- <a href="https://www.linkedin.com/">Estevao Ferreira Santos - RM567522</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/">Ana Cristina dos Santos</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/andregodoi/">Andre Godoi Chiovato</a>


## 📜 Descrição

O projeto AI4Success foca na detecção e classificação de objetos utilizando visão computacional, abordando duas frentes principais de implementação. A primeira consiste na detecção de objetos utilizando o framework YOLO, explorando tanto a abordagem de YOLO adaptável quanto o YOLO padrão. A segunda frente foca na classificação de imagens através de uma Rede Neural Convolucional (CNN) desenvolvida e treinada do zero.

O trabalho documenta todo o ciclo de vida do modelo, desde a organização do dataset até a avaliação crítica de métricas como precisão, recall, mAP e tempo de inferência. A documentação detalhada, decisões de implementação e análises completas estão centralizadas no notebook principal do projeto.


## 🔗 Links Rápidos
- **Notebook Completo (Jupyter/Colab):** [Acessar Notebook](https://colab.research.google.com/drive/1l2nWosIRdPEFrT6DG7Lvy5I2uWeRKGAg)
- **Vídeo Demonstrativo:** [Assistir no YouTube](https://youtu.be/I3DET0vRD8Y)


## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficam os arquivos de configuração específicos do GitHub para automação e gerenciamento do repositório.

- <b>assets</b>: Contém arquivos relacionados a elementos não-estruturados, como a logomarca da FIAP utilizada neste README.

- <b>Dados_fase6</b>: Pasta que armazena o dataset organizado para treino, validação e teste, incluindo subpastas para imagens, rótulos (labels) e o conjunto específico para a CNN.

- <b>Resultados_YOLO</b>: Armazena os artefatos gerados pelos treinamentos, como métricas de desempenho, gráficos de convergência, logs e os arquivos de pesos (.pt).

- <b>document</b>: Aqui está o notebook principal `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb`, que contém a documentação completa, experimentos e o passo a passo da solução.

- <b>README.md</b>: Arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).


## 🔧 Como executar o código

A execução detalhada está descrita no notebook do projeto, mas abaixo segue o resumo para configuração rápida:

1.  **Pré-requisitos**:
    * Python 3.10 ou superior.
    * Ambiente Jupyter Notebook ou acesso ao Google Colab.
    * GPU recomendada para o treinamento dos modelos YOLO e CNN.

2.  **Instalação**:
    Clone o repositório e instale as dependências necessárias:
    ```bash
    pip install torch torchvision ultralytics matplotlib pandas
    ```

3.  **Execução**:
    * Abra o arquivo `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb`.
    * Caso use o **Google Colab**, você pode carregar o notebook diretamente e ativar o ambiente de GPU em *Ambiente de Execução > Alterar tipo de ambiente de execução*.
    * Siga a execução sequencial das células para reproduzir os treinamentos e inferências.


## 🗃 Histórico de lançamentos

* 0.1.0 - 27/04/2026
    * Entrega da Fase 6: Implementação de YOLO (Padrão/Adaptável) e CNN do zero.


## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
