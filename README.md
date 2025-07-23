# PolyVTE: Polysemous Video-Text Evaluation for Video-guided Machine Translation

PolyVTE is a dedicated **English-Chinese evaluation dataset** designed to assess the disambiguation capabilities of Video-guided Machine Translation (VMT) models. It contains 232 curated video-text pairs where polysemous words require spatio-temporal visual context for accurate translation. For more details, refer to our ACM MM 2025 paper:  
_"Seeing Through Ambiguity: Effective Video-guided Machine Translation via Chaotic Fusion and Causally Aligned Spatio-temporal Attention"_  
([Paper PDF](https://doi.org/XXXXXXXX.XXXXXXX) | [GitHub](https://anonymous.4open.science/r/PolyVTE/)).

## Key Features
- **Targeted Evaluation**: Focuses on translation disambiguation of 80 English polysemous words with 222 distinct Chinese translations.
- **High-Quality Curation**:  
  - Videos retrieved from YouTube and manually filtered for semantic alignment
  - Bilingual annotations by professional translators
  - Each sample includes video, English source sentence, and reference Chinese translation
- **Dynamic Context**: Videos provide spatio-temporal cues to resolve ambiguities that static images cannot capture (e.g., motion semantics).

## Data Collection
Polysemous words were embedded in visually grounded contexts (e.g., `"Someone is doing something"`). Examples include:
[](@replace=1)

| Polysemous Word | Visual Context              | Source Sentence                     | Reference Translation       |
|-----------------|----------------------------|-------------------------------------|-----------------------------|
| **address**     | Writing on envelope        | _A woman is writing her address..._ | 一个人正在信封上写下地址。     |
| **address**     | Public speaking            | _A person in a suit is giving..._   | 一个穿着西装的人正在进行演讲。 |

![Uploading Example.png…]()


## License
CC BY-NC-SA 4.0: Non-commercial research use only.
