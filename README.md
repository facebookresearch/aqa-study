# Efficacy of Adversarial Data Collection for Question Answering
This repo contains the data (question/answer pairs and their associated passages from Wikipedia) collected and used in the following paper

Divyansh Kaushik, Douwe Kiela, Zachary C. Lipton, Wen-tau Yih. "On the Efficacy of Adversarial Data Collection for Question Answering Results from a Large-Scale Randomized Study." In ACL-IJCNLP 2021.

## Data format
The data has been arranged in two folders: BERT and ELECTRA, each corresponding to the model that was in the loop. Inside each directory, there are three sub-folders for each setting (fooled, random, and no-model). Each folder contains the training, validation, and test set files (formatted in the SQuAD JSON format) for the respective setting.

## Bibligoraphy

If you use our data, please cite the paper that introduced the resource with the following BibTeX:

```
@inproceedings{kaushik2021efficacy,
  title={On the Efficacy of Adversarial Data Collection for Question Answering Results from a Large-Scale Randomized Study},
  author={Kaushik, Divyansh and Kiela, Douwe and Lipton, Zachary C and Yih, Wen-tau},
  journal={Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (ACL-IJCNLP)},
  year={2021}
}
```

## License
Please check the LICENSE file.
