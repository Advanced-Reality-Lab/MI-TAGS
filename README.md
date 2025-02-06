# MI-TAGS Dataset

## Overview
MI-TAGS (Motivational Interviewing Transcripts Annotated with Global Scores) is a dataset designed to serve as a linguistic resource for language models, particularly in the fields of Natural Language Processing (NLP) and Psychology, specifically Motivational Interviewing (MI) research. This repository contains a sample of the MI-TAGS dataset in the form of CSV files.

## Dataset Description
The MI-TAGS dataset consists of transcripts annotated in Motivational Interviewing Treatment Integrity (MITI), which contains annotations at both the utterance level and the session level.

### Utterance Coding Sample CSV
This sample CSV file includes the following columns:
- **id**: Row id
- **Video Title**: Name of the video
- **Turn**: Index of the turn in the conversation
- **Speaker**: Identifier for the speaker (e.g., T for therapist, C for client)
- **Text**: Text of the utterance
- **Code**: Annotation code for the utterance
- **Annotator**: annotator id 
- **Normalized Turn**: Normalized version of the turn (if applicable)

### Global Scores Sample CSV
This sample CSV file includes the following columns:
- **id**: Row id
- **Video Title**: Name of the video
- **Annotator**: annotator id
- **Empathy**: Score for empathy
- **SofteningSustainTalk**: Score for softening sustain talk
- **CultivatingChangeTalk**: Score for cultivating change talk
- **Partnership**: Score for partnership
- **Only Text**: Text without tags
- **Tagged Text**: Text with tags
- **Only Tags**: Tags only

## Accessing the Full Dataset
To access the full MI-TAGS dataset, please fill out the access request form [here](https://advanced-reality-lab.github.io/MI-TAGS/). Additional requirements and instructions will be provided in the form.

## Publication and Conference Details
Our paper, titled "Motivational Interviewing Transcripts Annotated with Global Scores," was presented at the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024) held in Torino, Italia, in May 2024. The paper was honored with a nomination for Best Paper. You can access the publication through the ACL Anthology: https://aclanthology.org/2024.lrec-main.1017/.


## Citation
If you use the MI-TAGS dataset in your research, please cite it as follows:
```
@inproceedings{cohen-etal-2024-motivational,
    title = "Motivational Interviewing Transcripts Annotated with Global Scores",
    author = "Cohen, Ben  and
      Zisquit, Moreah  and
      Yosef, Stav  and
      Friedman, Doron  and
      Bar, Kfir",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.1017/",
    pages = "11642--11657",
    abstract = "Motivational interviewing (MI) is a counseling approach that aims to increase intrinsic motivation and commitment to change. Despite its effectiveness in various disorders such as addiction, weight loss, and smoking cessation, publicly available annotated MI datasets are scarce, limiting the development and evaluation of MI language generation models. We present MI-TAGS, a new annotated dataset of MI therapy sessions written in English collected from video recordings available on public sources. The dataset includes 242 MI demonstration transcripts annotated with the MI Treatment Integrity (MITI) 4.2 therapist behavioral codes and global scores, and Client Language EAsy Rating (CLEAR) 1.0 tags for client speech. In this paper we describe the process of data collection, transcription, and annotation, and provide an analysis of the new dataset. Additionally, we explore the potential use of the dataset for training language models to perform several MITI classification tasks; our results suggest that models may be able to automatically provide utterance-level annotation as well as global scores, with performance comparable to human annotators."
}
```
## Contact
For questions or inquiries about the MI-TAGS dataset, please contact bencohen3@gmail.com


