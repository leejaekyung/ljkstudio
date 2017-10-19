---
title: "Introduction"
weight: 2
---
<!-- The background to the work.

This paragraph contains one species, a _Hippopotamus amphibius_.

This sentence cites an article in the bibliography ([Author, 2014](https://example.com/articles/1)).

This sentence cites another article ([Author, 2015](https://example.com/articles/2)).

This paragraph has a DOI citation at the end, which supports this statement[👍](https://doi.org/10.1038/nature14388 "Cancer: Antibodies regulate antitumour immunity").

This paragraph [links to an article by DOI](https://doi.org/10.7717/peerj.182 "Ontogeny in the tube-crested dinosaur Parasaurolophus (Hadrosauridae) and heterochrony in hadrosaurids").

This paragraph [links to an article by PMID](http://www.ncbi.nlm.nih.gov/pubmed/25898005).

Equations and formula can be included either inline (<script type="math/tex"> 2+2=4 </script>) or as display blocks:

<div>\[ \sum_{i=0}^{\infty}\pi_i=\sum_{i=0}^{\infty}\rho^i\pi_0=\frac{\pi_0}{1-\rho}=1 \]</div> -->

카타르 국립 박물관 프로젝트를 수행하던 중, Secondary Steel Structure의 설치에서 현장 작업자가 정확한 설치를 어려워 하였다. 카타르 박물관은 수직 수평의 부재로 이루어지는 일반적인 건축물과 달리, 수백개의 원반형태의 구조물이 불규칙적으로 결합된 형상을 하고 있다. 때문에 공간에 수직 수평의 그리드에 맞춰서 시공하기 보다는 각 부재의 특수한 위치를 정확히 확인하여 설치해야 했다. 현장에서 부재의 정확한 위치를 확인하기 위한 측량도구로 토탈 스테이션을 사용하고 있다. 토탈 스테이션은 1회 측량에 단일 점의 위치만 확인할 수 있고 공간상의 점을 측량하기 어려우며,  XYZ의 좌표 값이 얻어지기 때문에 시각적으로 위치를 확인하기 어려워 측량에 많은 시간이 소요된다. 또한 부재의 좌표를 측량하기 위해서 부재 좌표를 모델과 도면으로부터 추출하여야 하는 추가적인 데이터 변환 프로세스가 요구된다. 이러한 데이터 전환을 거치는 점과 토탈스테이션의 단점을 개선하기 위해 현장에서 3D 모델을 정확한 위치에 나타낼 수 있는 방법을 연구하였다. 가상의 3D 모델과 현실 세계의 공간이 좌표 시스템의 일치를 통해 결합되기 위해 AR 기술을 적용하였다.

증강현실은 3D 그래픽 이미지를 다양한 방식의 디스플레이에 현실세계의 실시간 영상 등을 겹쳐 보이게 하여 현실과 가상을 혼합하는 기술로 P.Milgram 등에 의해 정의되었다. 가상현실Virtual Reality는 가상의 환경에 사용자가 몰입되어 실제 환경과 동떨어진 가상의 세계를 경험하는 기술이라면, 증강현실Augmented Reality는 현실과 가상이 결합되어 경계를 모호하게 하는 점에서 현실 환경이 증강 되었다는 개념이다.

 다이어그램에서 표현된바와 같이 건축 작업 환경에서 3D모델링은 컴퓨터 안에 존재하는 가상환경에 해당되며 현장은 현실 환경으로, 두 좌표세계를 연결하는 기술이 AR기술이라고 볼 수 있다.  다이어그램에서 AR은 현실을 우선적으로 가상 정보를 결합한다. 사용자의 현실에서의 움직임을 정교하게 추적하여 가상 정보를 실제 존재하는 것 처럼 느끼도록 디스플레이에 합성하는 기술이다. 정확한 합성을 위해 정확한 위치정보를 가상의 3D 좌표계와 일치시키는 기술이 필요하다. 사용자의 정확한 위치정보를 찾기위한 기술은 마커를 이용하는 방식과 주변 사물의 특징점을 활용하는 방식으로 나눌 수 있으나 모두 컴퓨터 비젼 기술에 기반하고 있다. 건설 현장에 적용하기 위해 상대적으로 연산량이 적은 마커 기술을 적용하였다.

 테스트 해본 결과 마커방식의 증강현실 기술은 마커가 인식되었을 경우에만 위치를 인식할 수 있고, 카메라 앵글에 마커가 80% 이하로 위치하는 경우에 마커 인식이 불가능 하여 증강현실이 중단되었다. 이러한 문제에 대응하기 위해 마커가 사라져도 위치인식을 유지하는 기술을 추가적으로 적용해야 한다.
 마커를 사용한 좌표계 정합시 발생하는 오차에 대해 Pentenrieder et. al(2006)의 논문에서 ARToolkit, Metaio, SCR marker system 등의 SDK는 같은 알고리즘을 사용하고 있으나 환경제약 조건, 하드웨어 등의 요인에 의해 정확성의 차이가 발생할 수 있다고 설명하고 있다. 
