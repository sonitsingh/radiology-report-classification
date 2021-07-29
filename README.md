# radiology-report-classification
Deep Active Learning for Annotation and Classification of Radiology Reports

This repository holds work for applying active learning for annotation of radiology reports and using state-of-the-art text classification models to categorise reports based on the severity of diseases. 

We use the Indiana University Chest X-ray Collection (IU-CXR) dataset [1]. The IU-CXR dataset is curated from two large hospitals within the Indiana network for patient care databases and can be publicly accessed through the open access biomedical image search engine (Open-i). The dataset consists of 7,470 chest X-ray and 3,955 radiology reports. Most of the studies have both the frontal and lateral views of chest X-rays. Each radiology report is in Extensible Markup Language (XML) format having tags for sections, namely, Comparison, Indication, Findings, and Impression. The impression section concludes the study by answering the clinical question. The data is fully de-identified following the Health Insurance Portability and Accountability Act (HIPAA) safe harbour guidelines. 

In this task, we aim to classify a radiology report into one of the four classes described below:
- Normal
- Abnormal, with no significant, acute or communicable findings
- Abnormal, with significant, acute or communicable findings not related to chest
- Abnormal



## References
[1] Demner-Fushman D, Kohli MD, Rosenman MB, Shooshan SE, Rodriguez L, Antani S, Thoma GR, McDonald CJ. Preparing a collection of radiology examinations for distribution and retrieval. J Am Med Inform Assoc. 2016 Mar;23(2):304-10. doi: 10.1093/jamia/ocv080. Epub 2015 Jul 1. PMID: 26133894; PMCID: PMC5009925.
