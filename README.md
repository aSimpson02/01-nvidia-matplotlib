# Let's learn matplotlib with Nvidia's timeline

A recipe: 27 years of Nvidia's share price, the chips that built it, and the scandal of November 2026, baked into one chart.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aSimpson02/01-nvidia-matplotlib/blob/main/main.ipynb)


## What you'll learn

- Fetching share prices with `yfinance`
- Side by side charts with `plt.subplots`
- Log scales with `set_yscale("log")`
- Labels and arrows with `annotate`
- Shading and marking dates with `axvspan` and `axvline`
- Styling: dark theme, custom colours, removing borders

## Ingredients

- Python 3.9+
- `yfinance`, `matplotlib`, `pandas`

## Run it

**In your browser:** click the Open in Colab badge above.

**On your machine:**

```bash
git clone https://github.com/aSimpson02/01-nvidia-matplotlib.git
cd 01-nvidia-matplotlib
python3 -m venv .venv
source .venv/bin/activate
pip install ipykernel yfinance matplotlib pandas
```

Then open `main.ipynb` and run the cells from top to bottom.

## Method

| Step | What happens |
|---|---|
| 1. Ingredients | Download daily closing prices since the 1999 IPO |
| 2. Menu | Map dates to product launches and scandal events |
| 3. Plate 1 | Full history on a log scale, with chip launches labelled |
| 4. Plate 2 | Zoom on October to November 2026 |
| 5. Garnish | Titles, grid, styling, save as PNG |

## Try it yourself

- Swap `"NVDA"` for `"AMD"` and plot both on the same axes
- Add a third plate for trading volume with `ax.bar()`
- Mark the 17 November earnings with another `axvline`

## Read the full article

On substack: [link when article is written]

*Data from Yahoo Finance via yfinance. For learning only, not financial advice!!*
