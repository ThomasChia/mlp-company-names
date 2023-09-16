# Neural Probabilistic Language Model Implementation

## Overview

This repository contains the implementation of the "A Neural Probabilistic Language Model" paper by Bengio et al. (2003). The project focuses on applying this language modeling technique to a dataset of company names. Language modeling is a crucial task in natural language processing (NLP) and has various applications, including text generation, speech recognition, and machine translation.

## Paper Reference

**Title:** A Neural Probabilistic Language Model <br>
**Authors:** Yoshua Bengio, Réjean Ducharme, Pascal Vincent, Christian Jauvin <br>
**Publication Year:** 2003 <br>
**Link:** [A Neural Probabilistic Language Model](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)

## Dataset

The dataset used in this project consists of company names. The data was pulled from Kaggle [here](https://www.kaggle.com/datasets/peopledatalabssf/free-7-million-company-dataset). It's essential to preprocess your dataset according to your specific requirements before using it for training and evaluation. Or else!

The data is read from a data folder, in a file saved as _companies\_sorted.csv_.

## Implementation Details

### Jupyter Notebook

The code for implementing the Neural Probabilistic Language Model is provided in a Jupyter Notebook. You can explore and run the code in the "src" directory. The notebook contains step-by-step instructions, code explanations, and comments to help you understand the implementation process.

### Dependencies

Make sure you have the following Python libraries and packages installed:

- [PyTorch](https://pytorch.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

You can typically install these dependencies using pip:

```
pip install torch numpy pandas matplotlib
```

Alternatively, you can just install the requirements.txt file with:
```
pip install -r requirements.txt
```

The choice is yours.
<br>


### Training
To train the Neural Probabilistic Language Model on your dataset, follow these steps:

1. Preprocess your dataset and organize it as required by the notebook.
2. Open the Jupyter Notebook mlp_company_names.ipynb.
3. Execute the code cells in the notebook, following the instructions provided.

### Evaluation
The notebook also includes sections for evaluating the trained model. You can assess the model's performance on various language modeling tasks, such as perplexity and text generation.

### Sampling the Model

Finally, the notebook has a section at the end where you can generate your own new company names. I will say, they are pretty terrible, just an FYI.

## Acknowledgments

I would like to express my sincere gratitude to the authors of the original paper, "A Neural Probabilistic Language Model," Yoshua Bengio, Réjean Ducharme, Pascal Vincent, and Christian Jauvin, for their pioneering work in the field of language modeling. Their research laid the foundation for this implementation.

Additionally, I appreciate the open-source community and resources that have been invaluable throughout this project.


## License

This project is licensed under the MIT License. Feel free to use and modify the code for your own research and applications. Refer to the LICENSE file for more details.

## Contact

If you have any questions or feedback, please don't hesitate to reach out:

- Thomas Chia
- tchia1997@gmail.com
- [chia.monster](https://chia.monster)