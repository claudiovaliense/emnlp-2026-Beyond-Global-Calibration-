# emnlp-2026-Beyond-Global-Calibration-
EMNLP 2026 Beyond Global Calibration: Analyzing Class-Specific Miscalibration and High-Confidence Errors in Text Classification

Link Article:
https://aclanthology.org/2026.uncertainlp-main.41/

Code in Colab:
[![View on GitHub](https://img.shields.io/badge/View%20Notebook-GitHub-black?logo=github)](https://github.com/claudiovaliense/emnlp-2026-Beyond-Global-Calibration-/blob/main/Beyond_Global_Calibration_Analyzing_Class_Specific_Miscalibration_and_High_Confidence_Errors_in_Text_Classification.ipynb)

## 📖 Citation

If you use this work in your research, please cite our paper:

> Claudio Moisés Valiense de Andrade et al. (2026). Analyzing Class-Specific Miscalibration and High-Confidence Errors in Text Classification. 

<strong>BibTeX</strong>

```bibtex
@inproceedings{andrade-etal-2026-beyond,
    title = "Beyond Global Calibration: Analyzing Class-Specific Miscalibration and High-Confidence Errors in Text Classification",
    author = "Andrade, Claudio Mois{\'e}s Valiense de  and
      Fonseca, Guilherme  and
      Cunha, Washington  and
      Fran{\c{c}}a, Celso  and
      Pagano, Adriana Silvina  and
      Rocha, Leonardo Chaves Dutra da  and
      Andr{\'e} Gon{\c{c}}alves, Marcos",
    editor = {Aziz, Wilker  and
      Berant, Jonathan  and
      Eikema, Bryan  and
      Ilia, Evgenia  and
      de Marneffe, Marie-Catherine  and
      Plank, Barbara  and
      Shelmanov, Artem  and
      Swayamdipta, Swabha  and
      Tiedemann, J{\"o}rg  and
      Vazhentsev, Artem  and
      V{\'a}zquez, Ra{\'u}l  and
      Zerva, Chrysoula},
    booktitle = "The Proceedings of the Third Workshop on Uncertainty-Aware {NLP}",
    month = oct,
    year = "2026",
    address = "Budapest, Hungary",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.uncertainlp-main.41/",
    doi = "10.18653/2026.uncertainlp-main.41",
    pages = "683--692",
    ISBN = "979-8-89176-486-6",
    abstract = "Confidence scores are increasingly used to assess uncertainty in text classification, yet aggregate calibration metrics may hide localized reliability failures. We investigate this issue across seven sentiment and topic classification datasets by comparing global and class-specific calibration and analyzing high-confidence errors. Our results show that low global calibration error can coexist with substantial class-specific variation, particularly in multi-class settings. We also find that high-confidence errors are not randomly distributed: they concentrate in specific true{--}predicted class confusions, with some incorrect predictions receiving confidence scores close to 1.0. These findings show that globally calibrated models can still exhibit systematic uncertainty failures, motivating class-aware and error-level analyses when confidence is used as an indicator of prediction reliability."
}
```
