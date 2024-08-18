풀스택 GPT

# 2.5 Virtual Environment 
1. python3.11 설치

2. 3.11 버전으로 가상환경 생성
python3.11 -m venv ./env

3. 가상환경 활성화
source ./env/bin/activate

4. 강의파일 설치
pip3 install -r requirements.txt 


source env/bin/activate
python main.py

# 3.0 LLMs and Chat Models
.env 파일에 api키를 이번 강의들으시면서 등록한경우 notebook.ipynb 파일을 재시작(Restart) 할것.//ㅈㅈ

llm = OpenAI() # 오류날때
llm = OpenAI(model_name="gpt-3.5-turbo-1106")
https://platform.openai.com/docs/deprecations 페이지에 따르면 1월 4일 기준으로 text-davinci-003 모델은 사용중단된 것 같습니다. 강의 내용이 동작하도록 저는 현재 서비스 되는 모델을 지정해서 진행했습니다.
