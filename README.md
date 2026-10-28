# sarima-pernambuco

Exercício de SARIMA (Financial Analytics, PADS Insper) aplicado ao índice de volume de vendas do **varejo ampliado de Pernambuco** (PMC/IBGE, sem ajuste sazonal).

- Relatório: [`index.html`](https://gustavojurema-dotcom.github.io/sarima-pernambuco/) (GitHub Pages)
- Fonte: `template-exercicio-sarima.qmd`

## Reproduzir

```bash
uv venv .venv
uv pip install -r requirements.txt
QUARTO_PYTHON=.venv/bin/python quarto render template-exercicio-sarima.qmd --output index.html
```
