# Awesome-Korean-NLP
- 소셜 미디어 분석을 위한 감정 분석 한국어 데이터 분석 관련 데이터셋을 정리합니다
- Topics
  - Sentiment and Emotion Analysis
  - Mental Health
  - Hate Speech


## Sentiment and Emotion Analysis
- [KSenticNet: 한국어 감성 사전 (Korean sentiment resource)](https://github.com/zzaebok/ksenticnet)
  - Analysis Unit: 단어
  - Output: sentic values, emotions (joy, surprise, fear, disgust, ...), polarity value and sentiments (negative, positive)
  
- [KNU 한국어 감성사전](https://github.com/park1200656/KnuSentiLex)
  - Analysis Unit: 단어
  - Output: polarity value and sentiments (negative, positive, netural)
  
- [네이버 영화 리뷰 데이터(Naver sentiment movie corpus v1.0)](https://github.com/e9t/nsmc#naver-sentiment-movie-corpus-v10_)
  - 네이버 영화 리뷰를 별점을 기준으로 긍/부정 분류
  - Analysis Unit: 문장
  - Output: sentiments (negative, positive)

- [KOSAC(Korean Sentiment Analysis Corpus)](http://word.snu.ac.kr/kosac)
  - Data collection (KOSAC): 332 뉴스기사에서 얻은 7,713개 단어
  - Analysis Unit: 단어
  - Output: polarity value and sentiments (negative, positive)
  - Shin, Hyopil, Munhyong Kim, Yu-Mi Jo, Hayeon Jang, and Andrew Cattle. 2013. KOSAC(Korean Sentiment Analysis Corpus): 한국어 감정 및 의견 분석 코퍼스, Information and Compuation, pages 181-190. [Paper](http://word.snu.ac.kr/kosac/publications.php) [Description](https://github.com/mrlee23/KoreanSentimentAnalyzer/blob/6bcaea9f37d536063d4c9703051f44b985374731/dic/readme.txt) [Python wrapper](https://github.com/mrlee23/KoreanSentimentAnalyzer)

- 한국어 트위터 감정 데이터
  - Data collection: 4,447 트윗
  - Output: Anger, Disgust, Fear, Happiness, Sadness, Surprise
  - Do, H. J., & Choi, H. J. (2015, October). Korean twitter emotion classification using automatically built emotion lexicons and fine-grained features. In Proceedings of the 29th Pacific Asia Conference on Language, Information and Computation: Posters (pp. 142-150). [Paper](https://www.google.com/url?client=internal-element-cse&cx=000299513257099441687:fkkgoogvtaw&q=https://aclanthology.org/2020.lrec-1.199.pdf&sa=U&ved=2ahUKEwjfh5je8u_1AhXBGKYKHf5hCswQFnoECAIQAQ&usg=AOvVaw0LVkjrGWuuUEIDiYOJUQI0) [Dataset](https://drive.google.com/drive/folders/0B_UtNNQhvjyCfkhoTjVNemdPaXZOV24wd1JUclg3RzVMTVpCb3JNbldOMU1rNkt0LTBVXzQ)

- [EmoNSMC](https://github.com/passing2961/EmoNSMC)
  - Weak labeling을 통해 구축된 데이터 (from [네이버 영화 리뷰 데이터(Naver sentiment movie corpus v1.0)](https://github.com/e9t/nsmc#naver-sentiment-movie-corpus-v10_))
  - [Korean Movie Review Emotion (KMRE) Dataset](https://github.com/passing2961/KMRE)의 향상된 버전 
  - Output: Anger, Disgust, Fear, Happiness, Sadness, Surprise
  - Lee, Y. J., & Choi, H. J. (2019). EmoNSMC: Constructing Korean Emotion Tagging Dataset Using Distant Supervision. In Annual Conference on Human and Language Technology (pp. 519-521). Human and Language Technology. [Paper](http://koreascience.or.kr/article/CFKO201930060624815.page)

- [GoEmotions-Korean](https://github.com/monologg/GoEmotions-Korean)
  - GoEmotions 데이터셋을 한국어로 번역한 후, KoELECTRA로 학습
    - GoEmotions: Reddit 추출된 58,000개 댓글
  - Analysis Unit: 문장
  - Output: Anger, Disgust, Fear, Happiness, Sadness, Surprise
  

## Mental Health
- [Korean Suicide Dictionary](https://github.com/DSAIL-SKKU/Cross-Lingual-Suicidal-Embedding) 
  - 인터넷 커뮤니티의 자살위험 텍스트에서 추출한 자살단어 사전
  - Analysis Unit: 단어
  - Lee, D., Park, S., Kang, J., Choi, D., & Han, J. (2020, November). Cross-Lingual Suicidal-Oriented Word Embedding toward Suicide Prevention. In Findings of the Association for Computational Linguistics: EMNLP 2020 (pp. 2208-2217). [Paper](https://aclanthology.org/2020.findings-emnlp.200/)

## Hate Speech
- [Korean HateSpeech Dataset](https://github.com/kocohub/korean-hate-speech)
  - 7,896개 문장 (from [네이버 영화 리뷰 데이터(Naver sentiment movie corpus v1.0)](https://github.com/e9t/nsmc#naver-sentiment-movie-corpus-v10_))
  - Analysis Unit: 문장 
  - Output: bias (gender, others, none), hate (hate, offensive, none)
  - Moon, J., Cho, W. I., & Lee, J. (2020, July). BEEP! Korean Corpus of Online News Comments for Toxic Speech Detection. In Proceedings of the Eighth International Workshop on Natural Language Processing for Social Media (pp. 25-31). [Paper](https://aclanthology.org/2020.socialnlp-1.4/)
  
- [욕설감지 데이터셋](https://github.com/2runo/Curse-detection-data)
  - 인터넷 커뮤니티 (일간베스트, 오늘의 유머 등) 5,825개 문장
  - Analysis Unit: 문장
  - Output: hate or not (binary)

- [Korean UnSmile Dataset](https://github.com/smilegate-ai/korean_unsmile_dataset)
  - 18,742 문장
  - Analysis Unit: 문장
  - Input: hate target (여성/가족, 남성, 성소수자, 인종/국적, 연령, 지역, 종교, 기타혐오, 악플/욕설) and non-hate



## Other Awesome Repositories
- [AwesomeKorean_Data](https://github.com/songys/AwesomeKorean_Data)
