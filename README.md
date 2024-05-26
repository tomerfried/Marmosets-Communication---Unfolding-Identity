# Marmoset Communication: Unfolding Identity

Welcome to our research repository on marmoset communication! This project delves into the fascinating world of vocal interactions among Common Marmosets, exploring whether these primates use specific calls to address individual members of their group—much like humans use names.


![חסר-שם](https://github.com/tomerfried/Marmosets-Communication---Unfolding-Identity/assets/68680809/74a7eee3-8270-4284-82af-d4a0c06f4f17)



## Abstract

Non-human primates were long thought to have limited ability to replicate and modify sounds. Recent studies challenge this view, suggesting some primates may possess vocal learning abilities. We explored this possibility in Common Marmosets, investigating if their calls include elements of individual identity. Specifically, we tested the hypothesis that marmosets use:
- **Global directed calls**: Common calls used by multiple individuals to address a specific marmoset.
- **Local directed calls**: Unique calls used by an individual to address a specific marmoset.

Using supervised learning methods, we found significant evidence for the existence of local directed calls, while global directed calls remained inconclusive.

## Methods and Techniques

### Data Collection (Performed by David Omer's laboratory, ELSC)
- **Vocalization Recording**: Recorded 45,000 vocalizations from 8 marmosets, focusing on pair interactions.
- **Spectrogram Generation**: Converted vocalizations into spectrograms for analysis.

### Data Preprocessing
- **Feature Selection**: Extracted key features from spectrograms.
- **Data Cleaning**: Undersampled data and removed outliers.

### Supervised Learning
- **Model Training**: Used algorithms to predict callee identity from vocalization patterns.
- **Single Caller Prediction**: Trained models on vocalizations from individual callers.
- **Cross-Caller Testing**: Tested models across different callers to check for consistency.

### Evaluation
- **Accuracy Metrics**: Measured model performance.
- **Visualization**: Used heatmaps to illustrate predictive accuracy.

These techniques helped us find evidence for local directed calls in marmosets, suggesting individuality in their communication.

![output](https://github.com/tomerfried/Marmosets-Communication---Unfolding-Identity/assets/68680809/5286119a-6afc-4f57-be34-3ce8e6a3a54a)

Example of a Phee call recording, processed into a spectrogram


## Key Findings

- **Single Caller Prediction**: Successfully predicted the identity of the callee based on calls from a single caller with above-chance accuracy.
- **Train on One, Test on Others**: Unable to predict callee identity when training on one caller's data and testing on others, suggesting the individuality of calls.

![dionysus no filter resized](https://github.com/tomerfried/Marmosets-Communication---Unfolding-Identity/assets/68680809/1405bfc7-930a-4878-95cd-184a24eeb605)

Phee calls made by an individual named Dionysus to other individuals. In the diagonal, an above chance level prediction is presented


## Future Work

- **Social Group Dynamics**: Investigate if specific social groups of marmosets develop unique global-identity calls through social learning.

## Acknowledgments

Special thanks to Prof. David Omer, Edmond & Lily Safra Center for Brain Sciences, The Hebrew University of Jerusalem

## Repo Content

In this repo, the notebooks of our research can be found. Our results and conclusions are based on this work, which is described in further details in the article.

## Contact

For any questions or collaborations, please reach out to us:

Guy Paul Hadad - Guyphadad@gmail.com

Tomer Fried - tomerfried96@gmail.com
