# KU-NLP-2020-2 디지털금융공학을 위한 자연어 처리 기술

### 0. 실행 환경
* Google `colab`환경에서 진행
* 런타임 유형: 하드웨어 가속기 (GPU), 런타임 구성 (고용량 RAM)
* `pytorch` 이용

### 1. NSMC 네이버 영화 리뷰 데이터 감정 분석
학습 데이터:`KOR_koelectra_v3_base/학습_데이터_model_kor_koelectra_v3_base.py` 또는 학습_데이터_model_kor_koelectra_v3_base.ipynb'  
테스트 데이터:`KOR_koelectra_v3_base/테스트_데이터_model_kor_koelectra_v3_base.py` 또는 테스트_데이터_model_kor_koelectra_v3_base.ipynb'  
테스트 데이터는 미리 학습 하여 dropbox에 저장한 모델을 다운로드하여 테스트를 진행하게 됩니다. 

- 학습 데이터 실행 방법
	1. KOR_koelectra_v3_base 폴더로 이동
	2. `학습_데이터_model_kor_koelectra_v3_base.ipynb `파일 오픈
	3. 모든 셀 실행을 통해 **1) 데이터 전처리, 2) 모델 구현 및 학습, 3) .pt로 학습모델 다운로드 가능**	

- 테스트 데이터 실행 방법
	1. KOR_koelectra_v3_base 폴더로 이동
	2. `테스트_데이터_model_kor_koelectra_v3_base.ipynb` 파일 오픈  
	3. 모든 셀 실행을 통해 **1) test set 다운로드, 2) 모델 다운로드, 3) 검증, 4) 예측결과 csv 파일 변환 및 다운로드** 가능  

- 데이터 출처  
[https://github.com/e9t/nsmc.git]

- 참고문헌 및 코드  
[http://kko.to/DhikTz8D0]
[https://github.com/google-research/electra]
[https://github.com/changdukkim/changdukkim-SA-Competition-BDC101]

### 2. 영문 Friends 드라마 대본 데이터 감정 분석  
학습 데이터:`EN_Bert_large/학습_데이터_model_bert_large.py` 또는 학습_데이터_model_bert_large.ipynb'  
테스트 데이터:`EN_Bert_large/테스트_데이터_model_bert_large.py` 또는 테스트_데이터_model_bert_large.ipynb'  
테스트 데이터는 미리 학습 하여 dropbox에 저장한 모델을 다운로드하여 테스트를 진행하게 됩니다. 


- 학습 코드 실행 방법
	1. EN_Bert_large 폴더로 이동
	2. `학습_데이터_model_bert_large.ipynb `파일 오픈
	3. 모든 셀 실행을 통해 **1) 데이터 전처리, 2) 모델 구현 및 학습, 3) .pt로 학습모델 다운로드 가능**	
	
- 검증 코드 실행 방법
	1. EN_Bert_large 폴더로 이동
	2. `테스트_데이터_model_bert_large.ipynb` 파일 오픈  
	3. 모든 셀 실행을 통해 **1) test set 다운로드, 2) 모델 다운로드, 3) 검증, 4) 예측결과 csv 파일 변환 및 다운로드** 가능  


- 데이터 출처  
[http://doraemon.iis.sinica.edu.tw/emotionlines/index.html]

- 참고문헌 및 코드  
[https://github.com/jiwonny/nlp_emotion_classification/blob/master/friends_electra.ipynb]
[https://github.com/google-research/electra]
[https://github.com/changdukkim/changdukkim-SA-Competition-BDC101]

* 참고 문헌 및 코드:  
Electra Large, KoBERT 참고 코드:  [https://github.com/jiwonny/nlp_emotion_classification]
