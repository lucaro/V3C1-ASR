# V3C1 ASR
This repository contains transcripts for the videos of the V3C1, the first shard of the Vimeo Creative Commons Collection. These transcripts have been generated using the public [Google Cloud Speech-to-Text API](https://cloud.google.com/speech-to-text/) set to use English. The results are stored in one file per video with the video id as file name. The files are encoded as JSON maps where the key refers to the shot number within the video and the value contains all the words spoken during this shot. For videos without any detected English speech, no file is present. All data is provided without any correctness guarantees. If you use the data provided in this repository, please cite the following corresponding publication:

## Bibtex
```
@inproceedings{vitrivrvbs2019,
  title={Deep Learning-Based Concept Detection in vitrivr},
  author={Rossetto, Luca and Parian, Mahnaz Amiri and Gasser, Ralph and Giangreco, Ivan and Heller, Silvan and Schuldt, Heiko},
  booktitle={International Conference on Multimedia Modeling},
  pages={616--621},
  year={2019},
  organization={Springer}
}
```
