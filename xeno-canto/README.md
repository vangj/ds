# Intro

This folder holds the notebooks to show how to apply machine learning to audio files. The audio files are taken from [xeno-canto](https://www.xeno-canto.org/), which has a database of bird sounds from around the world. In particular, we have downloaded all the bird sounds in the USA. Some techinques of [digital signal processing](https://en.wikipedia.org/wiki/Digital_signal_processing) (DSP) will be applied to the data, and some machine learning techniques on classification will be applied to the data.

Here is a description of the notebooks.

* [download-json.ipynb](download-json.ipynb) downloads the JSON referencing the audio files as well as the audio files themselves
* [explore-data.ipynb](explore-data.ipynb) explores the data at a high level with descriptive statistics
* [single-analysis.ipynb](single-analysis.ipynb) analyzes a single audio file
* [simple-classification.ipynb](simple-classification.ipynb) shows how to extract features from audio files and use machine learning clsasification techniques to classify one species of bird sound from another

For now, the vast majority of the code relies on the following resources.

* [LibROSA](https://librosa.github.io/librosa/index.html) as a audio processing API
* [Notes on Music Information Retrieval](https://musicinformationretrieval.com/index.html) as a reference and starting point on how to process audio files for music information retrieval
* [ffmpeg](https://www.ffmpeg.org/) as a command line tool to process audio files

# Copyright Stuff

```
Copyright 2018 Jee Vang

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```