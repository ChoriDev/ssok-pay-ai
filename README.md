1. Ollama 설치

``` shell
curl -fsSL https://ollama.com/install.sh | sh
```

2. Ollama 서버 실행

``` shell
ollama serve &
```

3. Gemma2 모델 다운로드

``` shell
ollama pull gemma2
```

4. langchain-ollama 패키지 설치

``` shell
pip install langchain-ollama
```