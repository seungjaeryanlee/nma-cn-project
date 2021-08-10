# Does engagement matter: Do mice see the world differently when they don't care?

The following repository contains code for the Project for Neuromatch Academy: Computational Neuroscience.

Traditionally V1/VISp is considered a simple feature detector. Stimulus representation in A1 is known to adapt to engagement in a go/no-go task. Does stimulus representation in V1 also differ depending on engagement (active) and disengagement (passive)? We investigate this question both cell-level and population-level.

## Requirements

Required Python packages are listed in the [requirements.txt](requirements.txt) file.
The dataset can be accessed from the following [allen-sdk api](https://allensdk.readthedocs.io/en/latest/visual_behavior_optical_physiology.html).

## Results 

- On single cell level our methods yield no clear results.
- Population level dissimilarity (RDM) hints at the difference between active and passive  session, but with control (pre-stimuli) this difference appears independent of the stimuli.

Refer to the respective notebooks for [single cell](single_cell_analysis.ipynb) and [population level analysis](population_analysis.ipynb). For detailed results, refer to the [presentation file](NMA-2021-AwareWolfs.pdf).

## References

- Bagur, S., Averseng, M., Elgueda, D., David, S., Fritz, J., Yin, P., Shamma, S., Boubenec, Y., & Ostojic, S. (2018). 
Go/No-Go task engagement enhances population representation of target stimuli in primary auditory cortex. Nature 
Communications, 9(1). https://doi.org/10.1038/s41467-018-04839-9 
- Kondo, M., & Matsuzaki, M. (2021). Neuronal representations of reward-predicting cues and outcome history with 
movement in the frontal cortex. Cell Reports, 34(5), 108704. https://doi.org/10.1016/j.celrep.2021.108704
- Kriegeskorte, N. (2008). Representational similarity analysis – connecting the branches of systems neuroscience. Frontiers 
in Systems Neuroscience. https://doi.org/10.3389/neuro.06.004.2008
- Montijn, J. S., Goltstein, P. M., & Pennartz, C. M. (2015). Mouse V1 population correlates of visual detection rely on 
heterogeneity within neuronal response patterns. ELife, 4, e10163. https://doi.org/10.7554/eLife.10163
- https://allensdk.readthedocs.io/en/latest/visual_behavior_optical_physiology.html
