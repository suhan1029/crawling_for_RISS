# crawling_for_RISS

- README를 제외한 4개 파일 다 다운받으시면 됩니다.

- **`KCI 우수등재, KCI 등재, KCI 등재후보`에 있는것만 가져오도록 수정하였습니다.**

- **각각 몇 페이지를 가져와야하는지 주석으로 표시해뒀습니다.**

- 2015~2024년의 논문을 수집하도록 하였습니다.

- 크롬 드라이버를 이용하여 실시간으로 접속해서 데이터가 수집되는 모습을 볼 수 있게 하였습니다. 다른 인터넷 작업을 하려면 크롬을 새로 열어서 평소 하듯이 하면 됩니다.

- 파일 다운 받고 아래의 명령어들을 터미널에서 실행해주시면 됩니다.

## 라이브러리 관련 명령어

- 일부 라이브러리의 버전 문제때문에 아래에 있는 명령들을 실행하시면 훨씬 편할겁니다.

  ```
  pip install bs4 selenium
  ```
  ```
  pip install kiwipiepy
  ```
  ```
  pip install wordcloud
  ```
  ```
  pip uninstall numpy scipy gensim networkx tensorflow matplotlib
  ```
  ```
  pip install numpy==1.24.0 scipy==1.10.0 gensim==4.3.1 networkx==3.0 tensorflow==2.14.0 matplotlib==3.6
  ```
