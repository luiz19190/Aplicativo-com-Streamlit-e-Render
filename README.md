# Aplicativo com Streamlit e Render

Primeiro app web que fiz com Streamlit no curso de Data Analyst da TripleTen: uma simulação de lançamentos de moeda que mostra a **Lei dos Grandes Números** na prática.

## O que faz

- Escolha o número de lançamentos (1 a 1.000) e clique em **Executar**.
- O gráfico de linha acompanha, lançamento a lançamento, a proporção de caras, que vai se aproximando de 0,5 conforme as tentativas aumentam.
- Cada experimento fica guardado numa tabela (número do experimento, tentativas e média final) enquanto a sessão estiver aberta.

## Como rodar

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Tecnologias

Python · Streamlit · pandas · SciPy (`scipy.stats.bernoulli`)

**Autor:** Luiz Trajano · [GitHub](https://github.com/luiz19190) · [LinkedIn](https://linkedin.com/in/luiz-antonio-trajano)
