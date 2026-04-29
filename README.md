# Fase6_Tarefa_AI4Success

![FIAP logo](assets/logo-fiap.png)

## Projeto

Entrega da Fase 6 — AI4Success: detecção e classificação de objetos. O trabalho aborda duas frentes principais:

- Detecção de objetos com YOLO (abordagens: YOLO adaptável — Entrega 1 — e YOLO padrão);
- Classificação com uma CNN treinada do zero.

**Informações do grupo**

- **Nome do grupo:** AI4Success
- **Turma:** 1TIAOR
- **Data:** 27/04/2026
- **Integrantes:**
  - Durval de Oliveira Dorta Junior - RM567007
  - Murilo Ferreira Borges - RM567738
  - Guilherme Cury - RM564011
  - Guilherme da Nobrega Gontijo - RM562211
  - Estevao Ferreira Santos - RM567522
- **Professores:**
  - Tutor(a): Ana Cristina dos Santos
  - Coordenador(a): Andre Godoi Chiovato

> Observação: o `README.md` funciona como porta de entrada e índice do projeto. A documentação completa, o passo a passo de execução, as decisões de implementação e a análise estão no notebook
> [GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb](GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb) (Jupyter/Colab).

---

## Sumário

- [Como navegar](#como-navegar)
- [Conteúdo do repositório](#conteudo-do-repositorio)
- [Estrutura de pastas](#estrutura-de-pastas)
- [Entregáveis do enunciado 2](#entregaveis-do-enunciado-2)
- [Como executar (resumo)](#como-executar-resumo)
- [Licença](#licenca)

---

## Como navegar

1. Abra o notebook `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb` para o passo a passo completo;
2. Use este `README.md` para encontrar rapidamente os artefatos e entender a organização do projeto;
3. Consulte a pasta `Resultados_YOLO` para ver métricas, gráficos e pesos gerados durante os experimentos.

## Conteúdo do repositório

- `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb`: documentação completa da solução (notebook/Colab);
- `Dados_fase6/`: dataset organizado para treino, validação e teste;
- `Resultados_YOLO/`: saídas dos treinamentos, métricas, gráficos e pesos;
- `LICENSE`, `README.md` e demais arquivos de apoio.

## Estrutura de pastas

Principais pastas e seu propósito:

- `.github/`: configurações do repositório no GitHub (ações, templates);
- `Dados_fase6/`: imagens e rótulos organizados para YOLO e CNN;
- `Dados_fase6/images`: imagens usadas nos experimentos;
- `Dados_fase6/labels`: rótulos para o conjunto YOLO;
- `Dados_fase6/cnn`: subconjunto preparado para treino da CNN;
- `Resultados_YOLO/`: métricas, gráficos, pesos e artefatos dos treinamentos.


## Entregáveis do enunciado 1

Esta seção lista os itens exigidos pelo Enunciado 1 e descreve objetivamente como cada item foi atendido neste repositório.

- Repositório com a solução: Atendido — este repositório público contém toda a solução, notebooks e artefatos relevantes.
- Notebook Jupyter/Colab executável: Atendido — o notebook principal está em `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb` e foi mantido com as saídas das execuções necessárias para a correção (células de código com resultados salvos sempre que aplicável).
- Células de código executadas e comentadas: Atendido — o notebook contém células de código com comentários e as principais células foram executadas para gerar métricas e exemplos de saída (gráficos e imagens) usados na análise.
- Células de markdown explicativas: Atendido — o relatório está organizado em seções em markdown que contextualizam decisões, descrevem a metodologia e apresentam conclusões e limitações do trabalho.
- Nome do arquivo conforme padrão: Atendido — o arquivo do notebook segue o padrão solicitado (`<Nome>_rm<XXXXX>_pbl_fase6.ipynb`).
- Vídeo demonstrativo (YouTube não listado): Pendente/Disponível — se houver um vídeo demonstrativo, adicione o link no README principal deste repositório; o campo está previsto e será incluído no README assim que o link for fornecido.

Observação: o `README_COLAB.md` deste repositório fornece um atalho direto para abrir o notebook no Google Colab e as instruções rápidas para execução (GPU, instalação de dependências, execução das células).

## Entregáveis do enunciado 2

Esta seção descreve os critérios de avaliação do Enunciado 2 e como eles foram cumpridos e documentados neste projeto.

- Abordagens avaliadas: Atendido — implementamos e avaliamos as três frentes solicitadas (YOLO adaptável, YOLO padrão e uma CNN treinada do zero). Os códigos e experimentos estão no notebook e os artefatos gerados estão organizados na pasta `Resultados_YOLO/`.
- Facilidade de uso/integração: Documentado — o notebook descreve como reproduzir cada experimento e as dependências necessárias; trechos de código e instruções de execução estão incluídos para replicação.
- Precisão do modelo: Documentado e mensurado — métricas de desempenho (precisão, recall, mAP ou acurácia para a CNN) estão presentes no notebook e nos arquivos de saída em `Resultados_YOLO/` (gráficos e CSVs quando aplicável).
- Tempo de treinamento/customização: Mensurado — os tempos de treinamento e configurações de hardware (quando registrados) foram anotados no notebook e, quando possível, salvos como parte dos artefatos de experimento.
- Tempo de inferência: Avaliado — há exemplos de inferência e medições de latência para as abordagens testadas (descritas no notebook e exemplificadas nas saídas geradas).
- Comparação crítica: Atendida — o notebook contém uma seção de análise comparativa que discute vantagens, limitações e trade-offs entre as abordagens (facilidade de uso, desempenho e custo computacional).

Onde encontrar os artefatos:

- Código e experimentos: `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb` (notebook principal).
- Resultados e pesos: `Resultados_YOLO/` (subpastas com curvas, imagens de validação, arquivos `.pt` de pesos e logs).

Nota de privacidade: mantenha o repositório público para avaliação pela equipe, mas evite expor links sensíveis que facilitem plágio; a descrição metodológica completa e os passos reprodutíveis estão centralizados no notebook.

## Como executar (resumo)

Este resumo orienta a execução rápida da solução; o passo a passo detalhado encontra-se no notebook/Colab.

Requisitos (exemplo): Python 3.10+, pip, bibliotecas listadas no notebook (torch, torchvision, yolov5 dependencies, etc.).

Exemplo rápido para reproduzir parte dos experimentos localmente:

```bash
# instalar dependências (exemplo)
python -m pip install -r requirements.txt

# abrir o notebook localmente
jupyter notebook GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb

# ou abrir em Colab: carregue o notebook no Google Colab e execute as células conforme instruções
```

## Licença

Consulte o arquivo `LICENSE` neste repositório para detalhes sobre a licença aplicada ao projeto.

---
