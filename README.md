## Sign-Language-Recognition-and-Intent-Detection
Sign languages (also known as signed languages)are languages that use thevisual-manual modality to convey meaning, instead of spoken words. Given a picture or videodata, recognize the sign language and detect intents.

## requirements

- pandas
- numpy
- zipfile
- matplotlib
- seaborn
- tensorflow
- visualkeras (pip install git+https://github.com/paulgavrikov/visualkeras --upgrade)
- JointBert (git clone https://github.com/monologg/JointBERT.git)

## Dataset

|       | Train  | Dev | Test  |   Labels      |
| ----- | ------ | --- | ----- | ------------- |
| MNIST | 27,455 | 500 | 7,172 | 24            |
| Snips | 13,084 | 700 | 700   | 7             |
| S/A   | 27,455 | 500 | 7,172 | 24            |

- The number of labels are based on the _train_ dataset.
- Add `UNK` for labels (For intent and slot labels which are only shown in _dev_ and _test_ dataset)
- Add `PAD` for slot label
