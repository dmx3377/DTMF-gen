# DTMF Signal Generator
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/dmx3377/dtmf-gen?style=for-the-badge)
![GitHub Created At](https://img.shields.io/github/created-at/dmx3377/dtmf-gen?style=for-the-badge)
![GitHub Downloads](https://img.shields.io/github/downloads/dmx3377/dtmf-gen/total?style=for-the-badge)
![Follow me on X](https://img.shields.io/badge/Follow_me-on_X-black?style=for-the-badge&logo=x&link=https%3A%2F%2Fx.com%2Fdmx3377)

___


This repository contains a Jupyter Notebook (`dtmf-gen.ipynb`) file that generates Dual-Tone Multi-Frequency (DTMF) audio signals. DTMF signals are the tones you hear when you press keys on a telephone.

##  `dtmf-gen.ipynb`

* This notebook contains Python code to generate DTMF tones for a given phone number.
* You can specify the phone number within the notebook.
* The notebook uses the  `numpy`  and  `IPython.display.Audio`  libraries to generate and play the audio.

##  Requirements

* [Python](https://www.python.org/) 3.x *or higher*
* [Jupyter Notebook](https://jupyter.org/)
* Python libraries:
    * numpy
    * IPython

##  Usage

1.  Clone the repository:
    ```bash
    git clone https://github.com/dmx3377/DTMF-gen.git
    cd DTMF-gen
    ```
2.  Open the  `dtmf-gen.ipynb`  notebook using Jupyter Notebook:
    `bash
    jupyter notebook dtmf-gen.ipynb
    `
3.  In the notebook:
    * Modify the  `DIAL_NUMBER`  variable in the last code cell to the phone number you want to generate DTMF tones for.
    * Run the notebook cells. The DTMF audio will be played.

##  License

This project is licensed under the [BSD 3-Clause License](LICENSE)

## Attribution
This repository uses *modified* portions of code taken from:
* [Hellochatterbox/OpenTone](https://github.com/HelloChatterbox/OpenTone)
* [alijamaliz/DTMF-detector](https://github.com/alijamaliz/DTMF-detector)
