```markdown
# Análise de Saldos Bancários 📊

Este projeto realiza uma análise exploratória inicial em um conjunto de dados contendo informações de contas bancárias e seus respectivos saldos de uma instituição financeira.

## 📋 Sobre o Projeto

O objetivo deste projeto é carregar, estruturar e analisar as informações de contas de clientes (`dados_contas`) para extrair estatísticas descritivas básicas, ajudando a entender a distribuição de recursos e os perfis de saldo dos clientes.

## 🗂️ Estrutura dos Dados

O arquivo de entrada utilizado é o `contas_saldos.csv`, que possui a seguinte estrutura:

| Coluna | Tipo de Dado | Descrição |
| :--- | :--- | :--- |
| **Conta** | `int64` | Identificador numérico único da conta bancária. |
| **Saldo** | `float64` | Valor monetário disponível na conta. |

### Sumário Estatístico dos Dados:
- **Total de Contas:** 15
- **Saldo Médio:** R$ 2.098,33
- **Saldo Mínimo:** R$ 73,30
- **Saldo Máximo:** R$ 4.934,29
- **Mediana (50%):** R$ 2.452,38

## 🛠️ Tecnologias Utilizadas

- **Python** (versão 3.x)
- **Pandas** para manipulação e análise de dados estruturados

## 🚀 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-seu-repositorio.git
```

2. Certifique-se de ter o arquivo `contas_saldos.csv` no diretório raiz ou ajuste o caminho da leitura no script.

3. Execute o script ou notebook Python:
```python
import pandas as pd

# Carregar os dados
dados_contas = pd.read_csv("contas_saldos.csv")

# Exibir informações gerais e estatísticas
dados_contas.info()
print(dados_contas.describe())
```

## 📈 Próximos Passos (Roadmap)
- [ ] Criar visualizações de distribuição dos saldos (histogramas e boxplots) usando `matplotlib` e `seaborn`.
- [ ] Identificar e categorizar clientes por faixas de saldo (ex: Baixo, Médio, Alto padrão).
- [ ] Identificar possíveis *outliers* (saldos excessivamente discrepantes).

---
Desenvolvido por [Seu Nome](https://github.com/seu-usuario) 😊
```
