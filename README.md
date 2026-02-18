# 📊 Governança de BI - Protheus

Repositório central para controle de versão do projeto **Clientes.pbip**. Este fluxo garante a rastreabilidade de alterações em medidas DAX e metadados do modelo.

## ⚖️ Regras de Negócio Implementadas

Conforme alinhamento técnico, o relatório segue as seguintes diretrizes:

- **Janela Temporal**: Filtro fixo de 90 dias a partir da data de emissão
- **Tratamento de Resíduos**: Pedidos com `C7_RESIDUO = 'S'` são desconsiderados
- **Produtos de Serviço**: Itens iniciados com dígito '9' possuem lógica diferenciada para status de recebimento

## 🛠️ Tecnologias

- Power BI Project (.pbip)
- Git / GitHub (Controle de Versão)
- TMDL (Tabular Model Definition Language)

---

*Mantido por Thiago Novais - Analista de BI Sênior*