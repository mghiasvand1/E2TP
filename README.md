<p>This repository contains the code implementation and data used for the paper titled "<a href="https://arxiv.org/pdf/2405.06454">E2TP: Element to Tuple Prompting Improves Aspect Sentiment Tuple Prediction</a>".</p>

### Abstract
Generative approaches have significantly influenced Aspect-Based Sentiment Analysis (ABSA), garnering considerable attention. However, existing studies often predict target text components monolithically, neglecting the benefits of utilizing single elements for tuple prediction. In this paper, we introduce Element to Tuple Prompting (E2TP), employing a two-step architecture. The former step focuses on predicting single elements, while the latter step completes the process by mapping these predicted elements to their corresponding tuples. E2TP is inspired by human problem-solving, breaking down tasks into manageable parts, using the first step’s output as a guide in the second step. Within this strategy, three types of paradigms, namely E2TP(diet), E2TP(f_1), and E2TP(f_2), are designed to facilitate the training process. Beyond dataset-specific experiments, our paper addresses cross-domain scenarios, demonstrating the effectiveness and generalizability of the approach. By conducting a comprehensive analysis across 10 different datasets for dataset-specific experiments, as well as 6 different states for cross-domain experiments, we show that E2TP achieves new state-of-the-art results in nearly all cases in terms of the F1 score evaluation metric.

### Citation
If you find our paper useful for your work or research, please kindly cite it:
```
@article{mohammadkhani2024e2tp,
  title={E2TP: Element to Tuple Prompting Improves Aspect Sentiment Tuple Prediction},
  author={Mohammadkhani, Mohammad Ghiasvand and Ranjbar, Niloofar and Momtazi, Saeedeh},
  journal={arXiv preprint arXiv:2405.06454},
  year={2024}
}
```
