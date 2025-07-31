# PolyVTE: Polysemous Video-Text Evaluation for Video-guided Machine Translation

PolyVTE is a dedicated **English-Chinese evaluation dataset** designed to assess the disambiguation capabilities of Video-guided Machine Translation (VMT) models. It contains 232 curated video-text pairs where polysemous words require spatio-temporal visual context for accurate translation. For more details, refer to our ACM MM 2025 paper:  
_"Seeing Through Ambiguity: Effective Video-guided Machine Translation via Chaotic Fusion and Causally Aligned Spatio-temporal Attention"_  
([Paper PDF](https://doi.org/10.1145/3746027.3755633) | [GitHub](https://github.com/zheng5d/PolyVTE)).

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


<a href="https://www.zupimages.net/viewer.php?id=25/30/z1sz.png"><img src="https://www.zupimages.net/up/25/30/z1sz.png" width="700" height="550" /></a>

## Citation
```
@inproceedings{zheng2025seeing,
  title = {Seeing Through Ambiguity: Effective Video-guided Machine Translation via Chaotic Fusion and Causally Aligned Spatio-temporal Attention},
  author = {Zheng, Jiawei and Liu, Feiyan and Wang, Xiaoli},
  booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia (MM '25)},
  month = oct,
  year = {2025},
  address = {Dublin, Ireland},
  publisher = {Association for Computing Machinery},
  location = {New York, NY, USA},
  url = {https://doi.org/10.1145/3746027.3755633},
  doi = {10.1145/3746027.3755633},
  pages = {1--9}
}
```
## License
CC BY-NC-SA 4.0: Non-commercial research use only.
