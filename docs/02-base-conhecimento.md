# Base de Conhecimento

## Dados Utilizados


| Arquivo | Formato | Para treinamento do agente |
|---------|---------|---------------------|
| `transacao_financeira_sample_set_1.csv` | CSV | Simula transações financeiras |
| `transacoes_orçamentaria_pessoal.csv` | CSV | Simula extrato e calcula gastos mensais |
| `transacoes.csv` | CSV | Analisar padrão de gastos do cliente |

fonte de dados: Kaggle e Hugging Face.

---

## Adaptações nos Dados

> Você modificou ou expandiu os dados mockados? 

Os dados utilizados foram modificados com a inserção  de dados pertinentes a funcionalidade prevista para o agente financeiro, como o de transações financeiras , geradas sinteticamente
para teinamento e desenvolvimento de IA/ML. Além de dados de transações de orçamento pessoal.


## Estratégia de Integração

### Como os dados são carregados?
> Descreva como seu agente acessa a base de conhecimento.
...python
import pandas as pd
import json

#csv

...

### Como os dados são usados no prompt?
> Os dados vão no system prompt? São consultados dinamicamente?

[Sua descrição aqui]

---

## Exemplo de Contexto Montado

> Mostre um exemplo de como os dados são formatados para o agente.

```
Dados do Cliente:
- Nome: João Silva
- Perfil: Moderado
- Saldo disponível: R$ 5.000

Últimas transações:
- 01/11: Supermercado - R$ 450
- 03/11: Streaming - R$ 55
...
```
