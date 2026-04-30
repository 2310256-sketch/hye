📊 한글 텍스트 시각화 및 워드클라우드 생성기
이 프로젝트는 사용자가 입력한 한글 텍스트를 분석하여 단어 빈도수를 계산하고, 이를 시각적으로 보여주는 워드클라우드(Word Cloud)를 생성하는 Streamlit 웹 애플리케이션입니다.

✨ 주요 기능
한글 텍스트 분석: 입력된 문장에서 단어별 출현 빈도를 자동으로 계산합니다.

데이터 시각화: 가장 많이 등장하는 단어 TOP 10을 표(Dataframe)로 보여줍니다.

워드클라우드 생성: 분석된 빈도수를 바탕으로 직관적인 워드클라우드 이미지를 생성합니다.

한글 폰트 완벽 지원: 나눔고딕(NanumGothic) 폰트를 적용하여 한글 깨짐 문제를 해결했습니다.

🛠 사용 기술 (Tech Stack)
Language: Python

Web Framework: Streamlit

Visualization: Matplotlib, WordCloud

Data Analysis: Pandas

NLP (Morphology): Bareunpy (또는 기본 공백 분리)

🚀 실행 방법 (Local)
리포지토리를 클론합니다.

Bash
git clone https://github.com/사용자계정/리포지토리이름.git
필요한 패키지를 설치합니다.

Bash
pip install -r requirements.txt
스트림릿 앱을 실행합니다.

Bash
streamlit run app.py
📂 파일 구성
app.py: 스트림릿 메인 애플리케이션 코드

requirements.txt: 프로젝트 실행에 필요한 라이브러리 목록

NanumGothic.ttf: 한글 출력을 위한 폰트 파일

README.md: 프로젝트 설명 파일
