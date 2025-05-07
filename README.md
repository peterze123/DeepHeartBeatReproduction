# DeepHeartBeatReproduction
#### This is an attempt to reproduce the paper DeepHeartBeat for the class UIUC DLH Spring 2025
#### The paper link: https://proceedings.mlr.press/v136/laumer20a.html
#### Paper's github link: https://github.com/laumerf/DeepHeartBeat/tree/master

#### Included in this repository:
DeepHeartBeatReproduction.ipynb: the notebook that we worked on, which contains our attempt to run the ecg.py and echo.py from paper's repository (although were note sucessful), and the mode training for a naive ECG model with evaluation on reconstruction error and Anamoly Detection. The model is created from the help of utility tools as well as LLM, although we have taken the functions that are reproducable from the paper's repository and embedded to the notebook.

Folders like cache, self_trained_modles are our attempt to run ecg.py and echo.py following the paper's utilitu functions, although we were not successful

### Data prepration
1. PhysioNet data: download [training2017](https://physionet.org/content/challenge-2017/1.0.0/training2017.zip) and expand into the folder physio_training in data directory
2. EchoNet data (was not able to fully expand while working): download from [EchoNet](https://echonet.github.io/dynamic/) unzip to folder Echonet-Dynamic in data directoy

### Citation 
@InProceedings{pmlr-v136-laumer20a,
title = "DeepHeartBeat: Latent trajectory learning of cardiac cycles using cardiac ultrasounds",
author = "Laumer, Fabian and Fringeli, Gabriel and Dubatovka, Alina and Manduchi, Laura and Buhmann, Joachim M.",
booktitle = "Proceedings of the Machine Learning for Health NeurIPS Workshop",
pages = "194--212",
year = "2020",
editor = "Emily Alsentzer and Matthew B. A. McDermott and Fabian Falck and Suproteem K. Sarkar and Subhrajit Roy and Stephanie L. Hyland",
volume = "136",
series = "Proceedings of Machine Learning Research",
month = "11 Dec",
publisher = "PMLR",
pdf = "http://proceedings.mlr.press/v136/laumer20a/laumer20a.pdf",
url = "http://proceedings.mlr.press/v136/laumer20a.html"
}
