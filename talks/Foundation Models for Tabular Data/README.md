# Foundation Models for Tabular Data

In 2022, a paper with a provocative title asked why tree-based models still beat deep learning on tabular data. Its answer was uncomfortable for anyone betting on neural networks: tables are not text. Their numbers are not words, their columns have no order, and their target functions are jagged in ways neural networks are biased to smooth over. LLMs, built for sequences of tokens, inherit every one of those weaknesses.

Four years later, transformers top the tabular leaderboards, but not because someone scaled an LLM. The winners kept the transformer block and in-context learning and replaced everything around them. This talk walks through four of those replacements, each as a problem, its fix and the improvement that followed: a numeric tokenizer instead of a text one, attention shaped like a table instead of a sentence, synthetic worlds instead of an internet to pretrain on, and a context that fits a million rows. We end with a rematch against the 2022 benchmark, and an honest look at where trees still win.

## Where it was held

- [Gen]AI Italy meetup M16 "Non solo LLM", Talent Garden Calabiana, Milano, Italy, 18 November 2026

## Slides

[Foundation Models for Tabular Data.pdf](Foundation%20Models%20for%20Tabular%20Data.pdf)
