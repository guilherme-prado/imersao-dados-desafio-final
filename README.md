
# Desafio Final Imersão Dados
# Tema: Drug Discovery
# Predição de mecanismos de ação possivelmente relacionados a tratamento de ansiedade, depressão e distúrbios alimentares.

## Apresentação 

Nesse estudo utilizando uma base de dados de mecanismos de ação e suas respectivas expressões gênicas dado uma lista de compostos aplicados em 2 dosagens diferentes em tempos de 24, 48 e 72 horas, desejo checar a acurácia de previsão para mecanismos de ação relacionados com tratamento de ansiedade, depressão e distúrbios alimentares.

Minha análise, apesar de direcionada aos mecanismos de ação descritos em artigos da Wikipedia sobre os tratamentos listados acima, será bem ingênua pois posso estar excluindo fatores extremamente relevantes para uma análise melhor direcionada.

Dito isso, minha análise será baseada nos seguintes mecanismos de ação:

* serotonin_receptor_agonist
* serotonin_receptor_antagonist

## Conclusão
Esse foi um estudo inicial para demonstrar que é possível, utilizando os mais adequados modelos de predição, determinar que a partir das expressões gênicas, determinar que os mdas do nosso estudo serão ativados. Verificamos que um modelo de árvore de decisão foi capaz de alcançar aproximadamente 99% de acurácia.

Verificamos também que é possível, desde que seja feita uma análise mais detalhada, dizer quais expressões gênicas podem estar relacionadas com a ativação desses mdas.

Nesse estudo, não foi levado em consideração a viabilidade celular das amostras, mas seria relevante filtrar nos resultados, as amostras que apresentaram maior viabilidade celular.

### Notebook
O passo a passo do estudo se encontra em: https://github.com/guilherme-prado/imersao-dados-desafio-final/blob/main/Notebooks/Drug_discovery_Guilherme_Prado.ipynb

### Dados utilizados:
https://github.com/guilherme-prado/imersao-dados-desafio-final/tree/main/Dados
