# Gráfico 5.29 — CO

Gráfico interativo em Python + Plotly baseado no arquivo `Dd_grafico_5_29.csv`.

## Dados
- Campo das estações: `estacao`.
- O CSV contém anos de 2007 a 2025.
- Para reproduzir a imagem de referência, o gráfico exibe **2016–2025**.
- Valores com vírgula decimal são convertidos automaticamente.
- Valores ausentes permanecem como lacunas.

## Configuração
- Eixo Y: 0–3 ppm.
- Intervalos: 1 ppm.
- Fundo: `#DDE9F4`.
- Grade horizontal pontilhada.
- Uma série por estação.
- Marcadores diferenciados.
- Tooltip interativo.
- Zoom.
- HTML autocontido.

## Arquivos
- `index.html`
- `Dd_grafico_5_29.csv`
- `gerar_grafico.py`
- `.github/workflows/pages.yml`
- `.nojekyll`
- `publicar_github.bat`
- `README.md`

## Gerar
```bash
pip install pandas plotly
python gerar_grafico.py
```

## Publicar
```bash
git init
git add .
git commit -m "Adicionar grafico 5.29 CO"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
```

No GitHub:
**Settings → Pages → Build and deployment → Source → GitHub Actions**
