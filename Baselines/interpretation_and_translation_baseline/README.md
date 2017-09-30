# AI_Challenger
Interpretation and translation (English to Chinese) baseline for AI_Challenger dataset.
# Requirenments
- python 2.7
- TensorFlow 1.2.0
- tensor2tensor
- jieba 0.39

# Prepare Data
Run the prepare script

cd prepare_data

./prepare.sh

# Train Model
Run the training script

./run.sh 1

# Inference
./inference.sh


# References

Attention Is All You Need

Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin

Full text available at:https://arxiv.org/abs/1706.03762
Code avalilabel at: https://github.com/tensorflow/tensor2tensor
