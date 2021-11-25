# ml_to_tree_to_rules
Criar um modelo preditivo com o algoritmo árvore de decisão e converter a árvore de decisão em regras textuais do tipo se então.

Utilize a base de dados disponibilizada (dataset.xls) para treinar um modelo preditivo do tipo árvore de decisão.
Em seguida gere um arquivo texto, ou uma saída no console com as regras da árovre de decisão em um formato textual de regras definido abaixo.

Formato da regra: 
SE VAR OP VAR ENTAO VAR OP VALOR

Exemplo de regra:
SE FEBRE > 37 ENTAO DOENÇA = GRIPE

![Arquitetura](https://github.com/giseldo/ml_to_tree_to_rules/blob/main/arquitetura.png)

OBS: Cada nó folha da árvore pode vir a ser uma regra
