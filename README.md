# ml_ex
머신러닝 사이킷런 실습

#
```
pip install streamlit
```


# streamlit 배포시 필수 사항
- os는 linux임, 인식하는 path로 변경해야함.
## 1. 파일 path
# ./  : 현재 디렉토리
base_path = os.path.dirname(__file__)


# requirements.txt 파일 생성방법
```
pip freeze > requirements.txt

예시
numpy @ file:///C:/miniconda3/conda-bld/numpy_and_numpy_base_1763980696204/work/dist/numpy-2.3.5-cp312-cp312-win_amd64.whl#sha256=bb8e9f7cb576c32f24212604430b2633f649dc00ee0a9d8d46e18853acc3c7f9
streamlit==1.51.0
scikit-learn @ file:///C:/b/abs_45qemhn4lg/croot/scikit-learn_1753427401078/work
joblib @ file:///C:/miniconda3/conda-bld/joblib_1757926366880/work
```
