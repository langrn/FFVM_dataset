# FFVM_dataset
**The dataset used by FFVM contains MIDI files and pre-processed npy files**

MIDI files are mainly piano versions of popular music. Every piece of midi can be recognized and appreciated by everyone.

**The following datasets are for reference**
- [MIDI Dataset](https://composing.ai/dataset)
- [Magenta Datasets](https://magenta.tensorflow.org/datasets/)
- [Lakh MIDI Dataset](https://colinraffel.com/projects/lmd/)

**The length distribution in this dataset, measured in one-sixteenth note lengths**
![image](https://github.com/langrn/FFVM_dataset/blob/master/images/length.png)

The main melody is extracted, noise removal is carried out, and stored as npy file.
notes_data.npy is processed from the entire dataset, while notes_data_flat.npy is processed from melodies with little change in pitch in the dataset.
