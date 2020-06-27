# R 개발환경 구축하기

- conda create -n R_env python=3.7
- conda install -c r r-essentials
- conda install jupyter notebook

- R 실행
    - install.packages('devtools')
    - devtools::install_github('IRkernel/IRkernel')
    - remotes::install_github('r-lib/pillar') (R kernel이 쥬피터노트북에서 안돌아갈 때, 설치해보기)
