### 한의학 진료보조 드로잉 노트 및 진료기록부 작성 시연영상
 - 진료보조 드로잉 노트
[![진료보조 드로잉 노트](http://img.youtube.com/vi/jlUAviuAuGk/0.jpg)](https://youtu.be/jlUAviuAuGk?t=1s) 

 - 진료기록부 작성기
[![진료기록부 작성기](http://img.youtube.com/vi/B_Gwzin0DAc/0.jpg)](https://youtu.be/B_Gwzin0DAc?t=1s) 


### Usage

1. 본 repository를 clone합니다.
```sh
git clone https://github.com/is2js/KoreanMedicineNote.git
```

2. 필요한 패키지들을 정리해놓은 `requirements.txt`를 통해 필요한 패키지 및 모듈을 설치합니다.
```python
pip3 install -r requirements.txt
```

3. Note.ipynb을 실행합니다.
 - 쥬피터노트북 혹은 vscode jupyter extension을 사용하셔도 됩니다.
```sh
jupyter notebook
# 혹은
code Note.ipynb
```


### 레포지토리 설명
1. `Note.ipynb`에서는 ipywidget 및 panel이라는 widget모듈을 활용해서 드로잉 노트와 한방 진료기록부 작성 코드를 불러옵니다.
2. 드로잉 노트는 기본적으로 `draw.py`에 정의된 widget들을 출력하며, 필요한 기본 의료이미지는 `images`폴더에서 불러옵니다.
3. 한방 진료기록부는  `form_progress.py`에 정의된 widget들을 출력하며, 다양한 혈자리와 부위는 내부에 dictionary자료구조로 정의되어있습니다. 그외에 panel widget를 통해 `disease_easy.db`에 저장된 수천개의 상병명을 자동완성으로 검색 및 입력할 수 있게 하였습니다.
4. `form_guide.xlsx`은 해당 프로젝트를 진행하면서 시각화하여 설계한 것이나 raw하여 정확한 내용을 인지하긴 어렵습니다. 참고용입니다.