**** 커뮤니케이션 & 국어학 전공 개발자 ****
**** Communication & Korean Language majored Engineer ****


"Korean_Grammatical_Kobert.ipynb" 파일은 국립국어원 <모두의 말뭉치>에서 21. 09. 15 ~ 21. 11. 01, 45일 간 진행한 인공지능 언어 능력 평가의 '문장 문법성 판단'에 대한 코드입니다. 다른 과제들과 달리, 문장 문법성 판단은 Matthew’s Corr를 기준으로 점수가 매겨졌습니다.

저는 SKT에서 pre-train한 KoBERT를 활용하여 해당 과제를 수행하였으며, 아래 RAVI TANWAR의 BERT for English Grammar Checking 글을 참고하여 코드를 작성하였습니다. 
(https://analyticsindiamag.com/how-to-use-bert-transformer-for-grammar-checking/)

과제의 Train, Dev, Test  데이터들은 국립국어원에 귀속되어있으므로, 업로드하지 않았습니다.

최종적으로, Mathew's Corr는 0.31정도 나왔고, 경쟁력 있는 점수가 아니어서 결국 순위권 안에 들지 못했습니다. 해당 공모전은 종료되었지만 저는 Mathew's Corr점수를 올리기 위해서 지속적으로 개선하고 있습니다



This file "Korean_Grammatical_Kobert.ipynb" is about codes of AI language comprehension evaluation hosted by National Institute of Korean Language <everyone's corpus> throughout the period from Sept 15th 2021 to Nov 1st 2021. Unlike other assignments, an assignment of sentence grammatical evaluation was scored based on Matthew's Corr.

I dealt with the Korean grammatical evaluation with using KoBERT pre-trained by SKT. In order to do, I referred to "BERT for English Grammar Checking" by RAVI TANWAR below and designed my own codes. 
(https://analyticsindiamag.com/how-to-use-bert-transformer-for-grammar-checking/)

Since copyright of all datasets(Train, Dev and Test) of this project belongs to National Institute of Korean Language, I don't upload them.

In conclusion, Matthew's Corr of my codes was recorded at 0.31, which was not so competitive that I could not take any prizes. Although the contest was over, I'm upgrading my codes continually to improve Matthew's Corr.
