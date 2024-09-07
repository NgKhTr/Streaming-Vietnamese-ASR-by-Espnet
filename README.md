# Streaming-Vietnamese-ASR-by-Espnet

- Training model from `STREAMING TRANSFORMER ASR WITH BLOCKWISE SYNCHRONOUS BEAM SEARCH` paper with Vietnamese dataset using Espnet framework on Kaggle environment
```
@inproceedings{tsunoo2021streaming,
  title={Streaming transformer asr with blockwise synchronous beam search},
  author={Tsunoo, Emiru and Kashiwagi, Yosuke and Watanabe, Shinji},
  booktitle={2021 IEEE Spoken Language Technology Workshop (SLT)},
  pages={22--29},
  year={2021},
  organization={IEEE}
}
```
- Vietnamese ASR dataset:
    - [Vin Big Data VLSP 2020 100h](https://www.kaggle.com/datasets/tuannguyenvananh/vin-big-data-vlsp-2020-100h).
    - [VIVOS](https://www.kaggle.com/datasets/tuannguyenvananh/vivos-dataset).
    - [Common Voice 13.0](https://huggingface.co/datasets/mozilla-foundation/common_voice_13_0): just use Vietnamese language.
- Preprocessing, training and evaluation with different tokenizations are divide in different stage base on Espnet framework because of time limitation in Kaggle:
  - Preprocessing: [data survey](https://www.kaggle.com/code/ngkhtrf/streaming-vietnamese-asr-espnet-data-survey), [data setup](https://www.kaggle.com/code/ngkhtrf/streaming-vietnamese-asr-espnet-data-setup)
  - Training
    - Char: [stage 1 - 10](https://www.kaggle.com/ngkhtrf/streaming-vietnamese-asr-espnet-stage-1-10-char), [stage 11](https://www.kaggle.com/code/ngkhtrf/streaming-vietnamese-asr-espnet-stage-11-char/notebook)
    - BPE:
    - Word: 
  - Evaluation:
    - Char: [stage 12 - 13](https://www.kaggle.com/code/ngkhtrf/streaming-vietnamese-asr-espnet-stage-12-13-char)
    - BPE:
    - Word: 
    - RTF/Latency calculation: 
- Inference: 
