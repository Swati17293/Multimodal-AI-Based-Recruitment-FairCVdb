
### Exploring Fusion Techniques in Multimodal AI-Based Recruitment: Insights from FairCVdb

Despite the large body of work on fairness-aware learning for individual modalities like tabular data, images, and text, less work has been done on multimodal data, which fuses various modalities for a comprehensive analysis. In this work, we investigate the fairness and bias implications of multimodal fusion techniques in the context of multimodal AI-based recruitment systems using the FairCVdb dataset. Our results show that <i>early-fusion</i> closely matches the ground truth for both demographics, achieving the lowest MAEs by integrating each modality's unique characteristics. In contrast, <i>late-fusion</i> leads to highly generalized mean scores and higher MAEs. Our findings emphasise the significant potential of <i>early-fusion</i> for accurate and fair applications, even in the presence of demographic biases, compared to <i>late-fusion</i>. Future research could explore alternative fusion strategies and incorporate modality-related fairness constraints to improve fairness.

<b>For additional insights, visit</b>: [https://swati17293.github.io/bias-in-fusion-EWAF24/](https://swati17293.github.io/bias-in-fusion-EWAF24/)

<div align="center">
	<img src="https://github.com/Swati17293/Multimodal-AI-Based-Recruitment-FairCVdb/blob/main/Abstract-EWAF.png" data-canonical-src="https://github.com/Swati17293/Multimodal-AI-Based-Recruitment-FairCVdb/blob/main/Abstract-EWAF.png" height="350"/>
</div>

Donwload the FairCVdb from [link](https://github.com/BiDAlab/FairCVtest/blob/master/data/FairCVdb.npy).
The scripts follow the experimental setup and hyperparameters defined in the FairCVtest testbed, available at [link](https://github.com/BiDAlab/FairCVtest/).

### References
[1] A. Peña, I. Serna, A. Morales, J. Fierrez, A. Ortega, A. Herrarte and M. Alcantara, “Human-Centric Multimodal Machine Learning: Recent Advances and Testbed on AI-based Recruitment”, in Springer Nature Computer Science, Vol. 4, n. 434, 2023.

### Cite As
```
@inproceedings{swati_swati17293,
  author       = {Swati Swati and Arjun Roy and Eirini Ntoutsi},
  title        = {Exploring Fusion Techniques in Multimodal AI-Based Recruitment: Insights from FairCVdb},
  booktitle    = {Proceedings of the 2nd European Workshop on Algorithmic Fairness (EWAF’24)},
  month        = {July},
  year         = {2024}
}
```
