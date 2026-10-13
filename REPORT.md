# Assignment 1 Report

*Delete this italic guidance as you fill in each section. You'll be asked to
defend any of this without your code in front of you — write only what you
can actually explain.*

- **Name**: Alexia Lara Chacon
- **Student ID**: 18964
- **Email**: alara.ieu2022@student.ie.edu
- **Group**: BBADBA 5B 

## Dataset

*What is it, where did you get it, what does one row represent, how many
rows/columns, and why did you pick it.*

I chose the Ames Housing dataset from a published journal called "Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project," Journal of Statistics Education 19(3) by Dean De Cock (2011). 
- **Source**:  Downloaded from jse.amstat.org via `scripts/download_data.py`, saved as `data/AmesHousing.csv`.
- **Size**: 2930 rows × 82 columns.
- **One row =** TODO: what exactly is one row? (Think: sale or property? Time period?)
- **Why I picked it**: I chose it because housing and real estate is a topic I am genuinely interested in and I consider it easy to understand when coding a project with it. I can easily correlate or understand what each column means, and I corroborated that it was a proper dataset to use for this project with Claude. 
- **Things I noticed in the raw data**: TODO: e.g. missing values, what "NA" means in some columns, outliers, skew in the price.


## Business / real-life framing

*The hypothetical scenario this model serves, and what that scenario implies
for how you built the pipeline — target definition, whether a time-based
split was necessary and why (or why not), which metric should drive the
decision threshold and why.*

- **Who uses the model**: TODO
- **Decision it supports**: TODO: what do they do differently based on the prediction?
- **When the prediction is made, and what information exists at that moment**: TODO
- **Target definition**: TODO: raw price or transformed? Why?
- **Which errors matter most to this user, and why**: TODO
- **Split strategy**: TODO: random or time-based? Why, given the 2006–2010 sale dates?
- **Metric that drives the decision, and why**: TODO
- **Columns excluded because they wouldn't be known at prediction time (leakage)**: TODO

## Data preparation & feature engineering

*What you engineered and why, and any data-quality decisions you made along
the way — e.g. "segment X had defective data, so I excluded it and used a
population-average default for scope Y at inference time; the impact of
that choice is Z."*

(Keep a running log. Add one entry per decision as you make it.)

| Decision | What I did | Why | Effect on results |
|---|---|---|---|
| TODO | | | |

- **Missing data handling**: TODO
- **Categorical encoding**: TODO
- **Transformations / new features**: TODO
- **Rows or columns dropped, and why**: TODO
- **How features the app user doesn't enter are filled in at inference**: TODO

## Modeling: three implementations, one model

*Which model (linear or logistic regression) and why. A results table
comparing scikit-learn, the manual PyTorch loop, and the standard
torch.nn.Module/torch.optim workflow, on the same test set, against the
naive baseline. Do the three agree? If not, why not?*

- **Model and why**: TODO
- **Naive baseline**: TODO
- **Hyperparameters I tuned (regularization, learning rate) and how**: TODO

| Method | Metric 1 | Metric 2 | Notes |
|---|---|---|---|
| Naive baseline | | | |
| scikit-learn | | | |
| Manual PyTorch loop | | | |
| torch.nn.Module + optim | | | |

- **Do the three agree?** TODO
- **If not, what did I investigate and what did I find?** TODO

## Limitations & next steps

*Real limitations you found, and concretely how you'd address each one with
more time or data — not generic hedging.*

| Limitation I found | How I'd address it |
|---|---|
| TODO | TODO |

## Generative AI use disclosure

*Per the syllabus AI Policy: what you used and how, or "no AI content used."*

- Claude (Anthropic): TODO: list what it was used for, e.g. locating the dataset, Codespaces/git setup, ... (add to this as you go)
- Everything else (framing, feature decisions, analysis, conclusions) is my own.


