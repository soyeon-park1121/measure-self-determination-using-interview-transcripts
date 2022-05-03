## Executive Summary
With development of Transformers, the accessibility to Natural Language Processing is getting easier. The interesting point is that all natural language processing have been done by using only regular description text data. However, it is difficult to find an example working on Natural Language Processing using interview transcripts. Since there are many differences between descriptions and dialogue, we cannot apply regular methods we used to analyze description text data, when we analyze interview transcripts. In this project, I explored and did experiments with Transformers to measure the level of self-determination of youth by using interview transcripts. I used two methods for this project. The first one is getting cosine similarity between the self-determination embeddings and transcripts’ embeddings. The second method is to fine-tune zero-shot classification to predict each sentence’s the level of self-determination. Since only 1.9% of the interview transcripts is related to the concept ‘self-determination’, both methods were not able to catch the level of self-determination correctly. However, I expect that the improved data’s quality will bring better results in the future. In addition, this project will help accelerate the development of NLP techniques on interview/conversation transcripts. 

## Introduction/Background
This project is an extension of a research studying the employment experiences of autistic adults, and understanding the factors influencing their employment, conducted by Julie Lounds Taylor, an associate professor of Pediatrics and Psychiatry & Behavioral Sciences. Her research team interviewed 185 families of youth with autism. Through the interviews, it is not difficult to measure “what” youth with autism is doing such as working for a company and studying in college. However, quantifying “how” they are doing and comparing the scores by manually reading the interview transcripts, are extremely challenging. One of the important factors to measure how they are doing is ‘self-determination’ of the youth. In this project, we are going to explore if Transformers can extract the level of ‘self-determination’ from interview transcripts. 

## Data
The data is 293 interview transcripts and the format is docx file.

## Methodology
1) Cosine similarity between self-determination and transcripts embeddings
2) Zero-shot classification

## Results
1) Cosine similarity
Some transcripts show close distance to self-determination embeddings than others

<img width="227" alt="image" src="https://user-images.githubusercontent.com/69788782/166554555-436928b6-bc1c-4d9a-8f0c-8d7cce07cfd9.png">

2) Zero-shot classification
After fine-tuning the zero-shot classification, I was able to get 64% of accuracy.

<img width="241" alt="image" src="https://user-images.githubusercontent.com/69788782/166554571-2b60588d-1d46-48ab-885e-8cc9b038531b.png">

## Contributors
Soyeon Park, M.S. in Data Science Candidate  
Vanderbilt University  
soyeon.park@Vanderbilt.Edu  

