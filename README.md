## Recurrent issues with DNN models of visual recognition

This repository contains data and code associated with *Maniquet, T., Op de Beeck, H. & Costantino., A. (2024) Recurrent issues with deep neural networks of visual recognition*.

### Data

Human and DNN data is contained within the `data` folder:
- `human_data.csv` contains the preprocessed and aggregated data from all 218 participants.
- `nn_data*.csv` files contain the aggregated performance results from all DNN models used in the experiment, split into <100mb chunks.

### Scripts

All the code necessary to reproduce the analyses and figures is contained in the `scripts` folder. Scripts are divided into sequential steps that follow the structure of the results section.

### Stimuli

All the stimuli from the human experiment are contained within the `stimuli` section. Images are divided into main manipulation conditions: _control_, _clutter_, _occlusion_ and _phase scrambling_. Each challenging manipulation contains sub-conditions, contained in separate sub-folders.