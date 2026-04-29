# Fase6_Tarefa_AI4Success

![FIAP logo](assets/logo.svg)

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

## Entregáveis do enunciado 2

Para cada abordagem realizada (YOLO adaptável feito na Entrega 1, YOLO padrão e CNN treinada do zero, esses últimos disponíveis nos capítulos de Redes Neurais), avalie criticamente os resultados comparando-os em termos de:

- Facilidade de uso/integração;
- Precisão do modelo;
- Tempo de treinamento/customização da rede (se aplicável);
- Tempo de inferência (predição).

O Jupyter notebook ou Colab integrado ao repositório contém a implementação e avaliação da solução e deve incluir:

- Código executado;
- Saídas (logs, métricas, imagens);
- Avaliações quantitativas e qualitativas;
- Células markdown avaliando criticamente os resultados e comparando as soluções implementadas.

> Nota de privacidade: mantenha os repositórios públicos para acesso da equipe interna da FIAP, mas evite expor links diretos sensíveis que possam facilitar plágio — a descrição metodológica detalhada está concentrada no notebook.

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

Se desejar que eu ajuste o inglês, adicione badges, ou gere um `README_COLAB.md` com instruções rápidas para abrir direto no Colab, diga qual opção prefere.