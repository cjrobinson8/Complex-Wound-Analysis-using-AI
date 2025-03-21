# Complex Wound Analysis using AI

[Journal Open Access Read Link](https://doi.org/10.1016/j.compbiomed.2025.109945) | [Hugging Face Repo](https://huggingface.co/cjrobinson8/complex-wound-analysis-using-ai) | [Cite](#cite)

Repository for publication outlining a number of computational models for complex wound analysis in both mice and humans.

## Abstract

Impaired wound healing is a significant clinical challenge. Standard wound analysis approaches are macroscopic, with limited histological assessments that rely on visual inspection of haematoxylin and eosin (H&E)-stained sections of biopsies. The analysis is time-consuming, requires a specialist trained to recognise various wound features, and therefore is often omitted in practice. We present an automated deep-learning (DL) approach capable of objectively and comprehensively analysing images of H&E-stained wound sections. Our model has a deep neural network (DNN) architecture, optimised for segmentation of characteristic wound features. We employed our model for the first-time analysis of human complex wounds. Histologically, human wounds are extremely variable, which presented a challenge when segmenting the different tissue classes. To validate our approach, we used mouse wound biopsy images across four timepoints of healing and employed the same DNN architecture for training and analysis in this context (89 % mean test set accuracy). We revised our approach for human complex wounds, analysing the biopsies at a cellular level, where our model performance improved (97 % mean test set accuracy). Together, our approach allows: (i) comprehensive analysis of human wound biopsy images; (ii) in-depth analysis of key features of mouse wound healing with accurate morphometric analysis and; (iii) analysis and quantification of immune cell infiltration, to aid clinical diagnosis of human complex wounds.

## Data Availability

The data that support the findings of the human study are from ComplexWounds@Manchester. Some restrictions apply to the availability of these data used under human patients’ study license. A sample of the data and the model that support the findings using the mouse-based wound model are available [here](https://huggingface.co/cjrobinson8/complex-wound-analysis-using-ai). A CC-BY-NC-ND-4.0 license has been applied to the research data/software arising from this study.

## License and Terms of Use
This model and associated data are released under the CC-BY-NC-ND 4.0 license and may only be used for non-commercial, academic research purposes with proper attribution. Any commercial use, sale, or other monetisation of the model and its derivatives, which include models trained on outputs from the model or datasets created from the model, is prohibited and requires prior approval. Downloading the model requires prior registration on Hugging Face and agreeing to the terms of use. By downloading this model, you agree not to distribute, publish or reproduce a copy of the model. If another user within your organisation wishes to use the model, they must register as an individual user and agree to comply with the terms of use. Users may not attempt to re-identify the deidentified data used to develop the underlying model. If you are a commercial entity, please contact the corresponding author.

## Contact
For any additional questions or comments, contact Connor Robinson (`connor.robinson@manchester.ac.uk`)

## Cite
If you found our work useful in your research, please consider citing our work at:

Connor J. Robinson, Bruce Dickie, Claudia Lindner, Jeremy Herrera, Lewis Dingle, Adam J. Reid, Jason K.F. Wong, Paul Hiebert, Timothy F. Cootes, Svitlana Kurinna,
Complex wound analysis using AI,
Computers in Biology and Medicine,
Volume 190,
2025,
109945,
ISSN 0010-4825,
https://doi.org/10.1016/j.compbiomed.2025.109945
