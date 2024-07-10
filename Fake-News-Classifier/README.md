### This dir contains, models for Fake News Classifier - Kaggle competitions
**Link : [https://www.kaggle.com/competitions/fake-news](https://www.kaggle.com/competitions/fake-news)**

| Architecture | Model | Embedding | Embedding Dimensions | Epochs | Accuracy |
|--------------|-------|-----------|----------------------|--------|----------|
| **Dropout Regualrization + `2` layers of BiDirectional LSTMs** | [.h5](https://drive.google.com/file/d/1ZHv_VmMUEIbIRhEHs9udfF3B0OXmynHV/view?usp=drive_link) | spacy > glove > `en_core_web_md`  | 300 | 10 | `0.8933843374252319` |
| **Dropout Regualrization + `2` layers of BiDirectional LSTMs** | [.h5](https://drive.google.com/file/d/1eE7aDLfhjiEnjoByU60usA0ZEH5Ibd_4/view?usp=drive_link) | tensorflow.keras.layers.Embeddings | 50 | 10 | `0.9070530533790588` |
