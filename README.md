# Sistema de IA para Recomendação de Receitas
## Descrição do Projeto
Sistema de inteligência artificial que recomenda receitas culinárias com base nos ingredientes disponíveis pelo usuário. O projeto utiliza técnicas de processamento de linguagem natural (PLN) para extração de ingredientes e aprendizado de máquina com Random Forest para prever a aceitação das receitas.

## Funcionalidades
Extração Inteligente de Ingredientes: Processamento de NLP para identificar e normalizar ingredientes de receitas

Sistema de Recomendação Personalizado: Modelo de IA que prevê a aceitação de receitas baseado em preferências

Filtro por Tempo de Preparo: Prioriza receitas rápidas (até 60 minutos)

Ordenação por Preferência: Classifica receitas por score de aceitação e avaliações

Combate ao Desperdício: Incentiva o uso integral dos ingredientes disponíveis

## Tecnologias Utilizadas
Python 3.12

Pandas - Manipulação de dados

Scikit-learn - Machine Learning (Random Forest)

Regex - Processamento de texto

Isodate - Conversão de tempo ISO

Google Colab - Ambiente de desenvolvimento

## Métricas do Modelo
### O modelo Random Forest alcançou excelente performance:

RMSE: 0.0071

R²: 0.9988

## Como Usar
Preparação do Ambiente
bash
### Instalar dependências
pip install pandas scikit-learn isodate kagglehub
### Execução
Execute o notebook Sistema_IA_para_Receitas.ipynb

O sistema carregará automaticamente o dataset de receitas

Digite os ingredientes disponíveis quando solicitado

Receba recomendações personalizadas ordenadas por preferência

## Interação
text
Digite seus ingredientes:
Quando terminar, digite 'fim'.

Ingrediente: tomate
Ingrediente: cebola
Ingrediente: alho
Ingrediente: fim

## Metodologia
Coleta de Dados: Dataset "Food.com Recipes and Reviews" com 500k+ receitas

Pré-processamento: Limpeza e padronização de ingredientes

Engenharia de Features: Criação do AcceptanceScore baseado em:

Tempo de preparo (preferência por ≤60min)

Categoria da receita

Avaliação dos usuários

Número de reviews

Modelo de ML: Random Forest para regressão do score de aceitação

Sistema de Recomendação: Filtragem por ingredientes + ordenação por preferência

## Resultados
Processamento de 514.494 receitas

Sistema capaz de sugerir receitas viáveis em tempo real

Redução do desperdício alimentar através do aproveitamento integral

Auxílio na tomada de decisão culinária diária

## Melhorias Futuras
Modelo de aprendizado por reforço para personalização contínua

Integração com restrições dietéticas e nutricionais

Monitoramento automático da dispensa via IoT

Expansão do banco de dados com receitas culturalmente adaptadas

## Desenvolvedores
André Arcuri Martins

Gabriel Da Silva Souza

Giulia Mota Apinagés Dos Santos

José Vitor Santos Alves

Guilherme De Luca Testoni Neiva Pereira

```http
  Projeto desenvolvido para a disciplina de Inteligência Artificial - Universidade Federal de São João del-Rei
```
