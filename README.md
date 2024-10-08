# CLIP Style Prompts in DG
Domain Generalization in Semantic Segmentation using CLIP Style Prompts   
**Junghyeon Seo**, Sungsik Kim, Seungheon Song, Jaekoo Lee, Korea Computer Congress 2024 (KCC 2024)  

[Paper Link](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11862149)  

## Method  
![image](https://github.com/junghyeon0427/KCC2024/assets/77001598/e47575dd-9369-42ec-86bf-45c79f68397c)

## Experimental Results (mIoU)
| Method                          | Cityscapes | Night  | Rain   | Snow   | Fog    |
|---------------------------------|------------|--------|--------|--------|--------|
| PØDA (Cityscapes → Night)       | 63.85      | <ins>**24.58**</ins>  | 41.54 | 44.34 | 50.93  |
| PØDA (Cityscapes → Rain)        | 63.87      | 22.92  | 40.78 | 43.49 | 50.41  |
| PØDA (Cityscapes → Snow)        | 64.31      | 21.38  | 40.21  | 43.69 | 50.43  |
| PØDA (Cityscapes → Fog)         | 63.25      | 22.44  | 38.04  | 41.31  | 48.44 |
| **Ours**                   | <ins>**64.78**</ins>   | 23.26  | <ins>**43.60**</ins>  | <ins>**44.69**</ins> | <ins>**52.44**</ins>  |

## Semantic Map Result
<img width="1116" alt="image" src="https://github.com/user-attachments/assets/cb1da318-424d-4f94-ba65-0fa80d258402">

## Reference Paper
We refer on the following paper  
[PromptStyler (ICCV 2023)](https://arxiv.org/abs/2307.15199), [PØDA (ICCV 2023)](https://arxiv.org/abs/2212.03241)
