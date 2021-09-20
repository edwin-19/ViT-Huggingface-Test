# Vision Transformers Test
Base code to test out how vision transformers work in comparison to a normal cnn
For this version i am using huggingfaces implementation - therefore pytorch

For this module i am using the ASL dataset to test out, you can download it [here](https://www.kaggle.com/grassknoted/asl-alphabet)

## Model Results
| Model Name                | Accuracy | MCC  |
|---------------------------|----------|------|
| ViT (Vision Transformers) | 1        | 0.99 |
| EffnetV2 B2 (2 Epochs)    | 1        | 0.99 |
| CNN (10 Epochs)           | 0.35     | 0.33 |

## ToDO
- [x] EDA
- [x] Train ViT model
- [x] Evaluate ViT model
- [x] Train & Evaluate Simple CNN
- [x] Train & Evaluate EffNetV2
- [ ] Inference Script