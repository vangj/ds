This folder holds the notebooks to show how to apply machine learning to audio files. The audio files are taken from [xeno-canto](https://www.xeno-canto.org/), which has a database of bird sounds from around the world. In particular, we have downloaded all the bird sounds in the USA. Some techinques of [digital signal processing](https://en.wikipedia.org/wiki/Digital_signal_processing) (DSP) will be applied to the data, and some machine learning techniques on classification will be applied to the data.

Here is a description of the notebooks.

* [download-json.ipynb](download-json.ipynb) downloads the JSON referencing the audio files as well as the audio files themselves
* [explore-data.ipynb](explore-data.ipynb) explores the data at a high level with descriptive statistics
* [single-analysis.ipynb](single-analysis.ipynb) analyzes a single audio file
* [simple-classification.ipynb](simple-classification.ipynb) shows how to extract features from audio files and use machine learning clsasification techniques to classify one species of bird sound from another