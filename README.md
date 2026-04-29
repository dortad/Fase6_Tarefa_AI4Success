# Fase6_Tarefa_AI4Success

Este repositório reúne a entrega da Fase 6 da AI4Success com foco em duas frentes complementares: detecção de objetos com YOLOv5 e classificação com CNN para as classes `trator` e `vaca`.

O README serve como porta de entrada do projeto. O passo a passo completo da solução, as decisões de implementação, os comandos executados e a análise detalhada dos resultados estão no notebook [GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb](GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb). A ideia aqui é orientar a navegação sem repetir a documentação extensa já consolidada no Jupyter/Colab.

## Como navegar

1. Comece pelo notebook para acompanhar a solução do início ao fim.
2. Use este README para entender rapidamente a finalidade do projeto e localizar os artefatos principais.
3. Explore as pastas de dados e resultados conforme necessário para validação ou reprodução.

## Conteúdo do projeto

- [GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb](GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb): documentação completa da solução, com execução em Colab/Jupyter.
- [Dados_fase6](Dados_fase6): dataset organizado para treino, validação e teste.
- [Resultados_YOLO](Resultados_YOLO): saídas dos treinamentos e artefatos gerados pelos experimentos.

## Organização das pastas

O projeto foi estruturado para manter os dados e os resultados separados do material explicativo:

- `Dados_fase6/images`: imagens usadas nos experimentos.
- `Dados_fase6/labels`: rótulos correspondentes ao conjunto YOLO.
- `Dados_fase6/cnn`: subconjunto preparado para a CNN.
- `Resultados_YOLO`: métricas, gráficos e pesos dos treinamentos.

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

Observação: o README mantém a visão geral e a direção para o notebook; a documentação completa e os passos de execução permanecem no `GuilhermeDaNobregaGontijo_562211_pbl_fase6.ipynb`.

## Observação

O repositório permanece público para facilitar o acesso da equipe interna da FIAP. Para evitar plágio ou uso indevido, a descrição metodológica completa fica concentrada no notebook, enquanto o README mantém apenas a visão geral e a orientação de acesso.