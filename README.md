# Avaliação A1 - Inteligência Artificial | UNITINS

Este repositório contém os arquivos utilizados na Avaliação 1 (A1) da disciplina de Inteligência Artificial do curso de Sistemas de Informação da UNITINS.

## Descrição da Atividade

A atividade consistiu em investigar o comportamento de uma Rede Neural Multicamadas (MLP) na resolução do problema lógico XOR, utilizando o código-base `mlp_simples.py`.

Foram realizados cinco experimentos, variando os seguintes parâmetros:
- Número de neurônios na camada oculta
- Taxa de aprendizagem
- Quantidade de épocas

Além da execução e registro dos testes, a atividade exigia uma apresentação explicativa em vídeo com gráficos de convergência e análise crítica dos resultados.

## Experimentos Realizados

1. 2 neurônios ocultos, taxa de aprendizagem 0.1, 1000 épocas  
2. 2 neurônios ocultos, taxa de aprendizagem 0.1, 10000 épocas  
3. 4 neurônios ocultos, taxa de aprendizagem 0.1, 1000 épocas  
4. 4 neurônios ocultos, taxa de aprendizagem 0.1, 10000 épocas  
5. 4 neurônios ocultos, taxa de aprendizagem 0.5, 10000 épocas

Foram gerados gráficos de erro (convergência) e analisado o desempenho da rede em cada configuração.

## Conteúdo do Repositório

| Arquivo | Descrição |
|--------|-----------|
| `mlp_simples.py` | Código da Rede Neural Multicamadas utilizada nos testes |
| `slides_apresentacao.pdf` | Slides utilizados para explicar o experimento durante o vídeo |

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
