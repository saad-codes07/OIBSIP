# Level 2 Task 5: Autocomplete and Autocorrect Data Analytics

## Overview
This project builds an NLP text prediction and spell-checking pipeline implementing frequency-based N-gram language models for autocomplete and Levenshtein edit-distance algorithms for autocorrect.

## Checklist Deliverables
* **Corpus & Preprocessing:** Tokenized and cleaned text dataset; computed vocabulary frequency distributions.
* **Autocomplete Engine:** Implemented Bigram and Trigram prediction models returning top 3 candidates for 10 test prefixes.
* **Autocorrect Engine:** Developed edit-distance correction algorithms tested across 20 misspelled terms.
* **Algorithm Comparison:** Evaluated standard Levenshtein distance vs. Damerau-Levenshtein (character transposition handling).
* **Performance Visualizations:** Plotted top 20 word frequency distributions and autocorrect accuracy breakdowns.
* **System Discussion:** Documented architectural limitations compared to production mobile keyboards (Gboard/iOS).