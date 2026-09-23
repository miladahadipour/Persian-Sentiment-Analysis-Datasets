# Insta-MultiDSenti Dataset

This dataset contains Persian Instagram comments across two domains: Celebrities and the Asre Jadid talent show. It is used for severe zero-shot cross-domain evaluation (Tier 3) in the paper.

## Files
- `Insta-MultiDSenti.xlsx` — Main dataset file (Excel format)
  > **Recommendation:** Convert to CSV for better compatibility.

## Columns
| Column | Description |
|--------|-------------|
| text   | Comment text in Persian |
| label  | Sentiment label (0 = Negative, 1 = Positive) |
| domain | Domain of the comment (Celebrities / Talent Show) |

## Source
The original dataset and benchmark details are available at:
[GitHub - BERT-crossDomain-sentiment-classification](https://github.com/mpanahi/BERT-crossDomain-sentiment-classification)

Also cited in:
> Panahandeh Nigjeh, M., & Ghanbari, Sh. (2024). Leveraging ParsBERT for cross-domain polarity sentiment classification of Persian social media comments. *Multimedia Tools and Applications*, 83, 10677–10694.

## Usage in the Paper
This dataset was used exclusively for **severe zero-shot cross-domain evaluation** (Tier 3), where the model trained on SnappFood was tested directly on Instagram comments without any fine-tuning, to assess robustness under **simultaneous topic, platform, and register shifts**.

## License
This dataset is released under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.
