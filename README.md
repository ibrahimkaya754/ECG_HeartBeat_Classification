# ECG_HeartBeat_Classification
Forked from "https://github.com/SajadMo/ECG-Heartbeat-Classification-seq2seq-model", very special thanks to SajadMousavi

## Recruitments
* Python 2.7
* tensorflow/tensorflow-gpu
* numpy
* scipy
* scikit-learn
* matplotlib
* imblearn

## Dataset
They evaluated the model using [the PhysioNet MIT-BIH Arrhythmia database](https://www.physionet.org/physiobank/database/mitdb/)
* To download our pre-processed datasets use [this link](https://drive.google.com/drive/folders/1TGg1413qa5TkcC0zF6CUDhKWlNzJgPCJ?usp=sharing), then put them into the "data" folder.

## Train

* Modify args settings in seq_seq_annot_aami.py for the intra-patient ECG heartbeat classification
* Modify args settings in seq_seq_annot_DS1DS2.py for the inter-patient ECG heartbeat classification

* Run each file to reproduce the model described in the paper, use:

```
python seq_seq_annot_aami.py --data_dir data/s2s_mitbih_aami --epochs 500
```
```
python seq_seq_annot_DS1DS2.py --data_dir data/s2s_mitbih_aami_DS1DS2 --epochs 500
```
## Results
  ![Alt text](/images/results.jpg)
## Citation
If you find it useful, please cite their paper as follows:

```
@article{mousavi2018inter,
  title={Inter-and intra-patient ECG heartbeat classification for arrhythmia detection: a sequence to sequence deep learning approach},
  author={Mousavi, Sajad and Afghah, Fatemeh},
  journal={arXiv preprint arXiv:1812.07421},
  year={2018}
}
```

## References
 [deepschool.io](https://github.com/sachinruk/deepschool.io/blob/master/DL-Keras_Tensorflow)
 
## Licence 
For academtic and non-commercial usage 
