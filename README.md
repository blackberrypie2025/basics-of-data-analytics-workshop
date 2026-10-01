# Data Analysis Workshop

A 3-hour, beginner-to-advanced introduction to data analysis in Python: cleaning a messy dataset, exploring it with charts, and building a simple prediction model — all in one self-contained Colab notebook.

No setup required. No real/personal data is used — the dataset is synthetically generated inside the notebook with a fixed random seed, so everyone who runs it gets the same numbers.

## Run it

**Option 1 — Open in Colab (recommended)**

Click the badge, or go to [colab.research.google.com](https://colab.research.google.com), choose **GitHub**, and paste this repo's URL.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Workshop_Colab_Notebook_Tiered.ipynb)

> Replace `YOUR_USERNAME/YOUR_REPO` above with your actual GitHub path once this is pushed, so the badge links correctly.

Once open, go to **File → Save a copy in Drive** before running anything, so your edits are kept.

**Option 2 — Run locally**

```bash
pip install -r requirements.txt
jupyter notebook Workshop_Colab_Notebook_Tiered.ipynb
```

## What's inside

| Section | Topic | Time |
|---|---|---|
| 1 | Foundations and Colab basics | 2:00–2:20 |
| 2 | Data storage and libraries (loading and cleaning a messy CSV) | 2:20–2:50 |
| 3 | Exploratory data analysis (histograms, scatter plots, boxplots) | 2:50–3:20 |
| — | Break | 3:20–3:35 |
| 4 | Inference and modelling (train/test split, linear regression, baseline comparison) | 3:35–4:05 |
| 5 | End-to-end project wrap-up (make your own change, write a conclusion) | 4:05–4:45 |
| 6 | Thank you & Q&A | 4:45–5:00 |

Every section has **optional tracks** so the same notebook works for a mixed-skill audience:

- 🟢 **Foundation support** — glossaries, "predict before you run" prompts, editable one-line cells
- 🟡 **Stretch** — ready-to-run cells that go one step further (statistical tests, extra charts, more metrics)
- 🔴 **Challenge** — write-your-own-function scaffolds, each with a collapsible worked solution

Progress trackers and checkpoints throughout keep the group paced together; the optional cells never block anyone from moving on.

## Requirements

Python 3.10+, with `pandas`, `numpy`, `matplotlib`, `scikit-learn`, and `scipy`. See `requirements.txt`. All of these come preinstalled in Google Colab, so Option 1 needs no setup at all.

## License

MIT — see `LICENSE`. Reuse, adapt, and remix freely for your own workshops.
