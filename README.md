# Non-intrusive-Speech-Quality-Models
Comparison of Non-Intrusive Deep Models for Predicting Overall Speech Quality

Model weights for fine-tuned and retrained versions of the single-ended speech quality prediction model, [NISQA](https://github.com/gabrielmittag/NISQA), are given here. Weights for the following three models are provided:

- Baseline model that is made of a deep feed forward component, followed by BiLSTM component, followed by average pooling.
- Fine-tuned NISQA model that is made of six CNN layers, followed by self-attention component, followed by attention-pooling.
- Retrained NISQA model.

**Instructions**

To use the baseline/fine-tuned/retrained weights, download the weight file (example retrained.tar) and refer to the open-source NISQA framework for executing prediction, evaluation, or further fine-tuning these weights.

**Usage**

If you use these model weights for your research, please cite the following paper: TBA

**Reference**

[G. Mittag, B. Naderi, A. Chehadi, and S. Möller “NISQA: A Deep CNN-Self-Attention Model for Multidimensional Speech Quality Prediction with Crowdsourced Datasets,” in Proc. Interspeech 2021, 2021.](https://www.isca-speech.org/archive/pdfs/interspeech_2021/mittag21_interspeech.pdf)
