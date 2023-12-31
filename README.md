# 1. 프로젝트 소개
## 특정 도메인에 특화된, 한국어를 사용하는 챗봇
KoAlpaca를 사용하여 특정 도메인에 관한 전문적 지식이 요구되는 질문시, 부적합한 답변을 출력한다.
기존에 존재하던 모델은 특정한 분야의 전문적 지식이 불충분하다는 것을 알게 되었고 이를 보완하고자 함.

<br>

# 2. 팀 소개
|최상준|김정민|김채원|
|------|---|---|
|정보컴퓨터공학과 201624597|정보컴퓨터공학과 201824448|불어불문학과 201902163|
|•키프리스 데이터셋 크롤링 및 전처리|•지식인 자연어 처리 모델 생성<br>•Web 구현|•지식인 데이터셋 크롤링|
|choi4th4570@pusan.ac.kr|kjmin017@gmail.com|bbubbune@naver.com|

<br>

# 3. 구성도
![2023포스터_05_응답하라챗봇_01085230874](https://github.com/pnucse-capstone/capstone-2023-1-05/assets/56316503/a01e4655-029a-4d18-a471-325cbb26ac4d)

<br>

# 4. 소개 및 시연영상
[![2023년 전기 졸업과제 05 응답하라 챗봇](http://img.youtube.com/vi/4sXLycFSg6g/0.jpg)](https://www.youtube.com/watch?v=4sXLycFSg6g)


<br>

# 5. 사용법
## 설치법<br>
1. https://huggingface.co/kjmin017/polyglot-ko-1.3b-base-knk<br>
https://huggingface.co/kjmin017/polyglot-ko-1.3b-lora-knk<br>
에서 두 모델 다운로드<br>
2. 각<br>
poly-pretrained<br>
LoRA<br>
폴더에 넣고<br>
```python
$ pip install -r requirements.txt
final.py
```
## 사용법<br>
1. text칸에 질문하고자 하는 내용을 입력한다.
2. text칸 밑의 Clear칸을 클릭하면 내용을 지울 수 있다.
3. text칸 밑의 Submit칸을 클릭하면 질문이 제출된다.
4. 질문에 대한 답변이 Output칸에 입력된다.
