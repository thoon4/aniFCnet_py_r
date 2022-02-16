# Research Project - Decoding temporal structure in narratives using functional connectivity pattern

## Index
  - [Authors](#authors) 
  - [About](#about) 
  - [Overview](#overview) 
  - [Abstract](#abstract)
  - [Files](#files)
  - [License](#license)

## Authors
- **Taehoon Kim**, Suhyun Lee, Seonhwa Park, Yeongeun Ban, & Ghootae Kim
- Deep Memory Lab, Cognitive Science Research Group, Korea Brain Research Institute

## About
- 이 Repository는 행동 및 fMRI 인지 실험의 데이터 분석 작업물을 담고 있습니다.
- 실험 프로그램와 fMRI 영상 데이터 전처리 등을 위한 코드, 개별 참가자의 원본 데이터는 포함되어 있지 않습니다. 
- 분석은 R과 R studio, Python, jupyter notebook를 통해 수행되었으며, 분석 코드 및 결과는 **aniFCnet_results.html** 를 다운로드받아서 확인하실 수 있습니다. 
- 다른 파일에 대한 정보는 아래 **FILES**를 확인해주세요.

## Overview
- 발단부터 결말에 이르는 이야기의 구조 이해 과정에서 뇌의 기능적 연결 네트워크 변화에 대한 fMRI 실험 연구 수행.
- 애니메이션 시청 중의 뇌 활성화를 측정, 이야기 이해 과정과 연결하여 다변량 패턴 분석을 수행.
- 네트워크 간 분화와 정보 통합 과정이 이야기 이해에 중요하며 FPN, DAN, DMN, VAN 등의 네트워크가 주요 역할을 한다는 것을 확인.

## Abstract

We perceive and memorize a set of continuous events as a narrative with plot structure, such as exposition, complication, climax, and resolution. Although many previous studies investigated how the brain constructs a unitary representation of a visual object consisting of many different parts, few studies examined how a temporal structure of narratives is represented in the brain. Here we investigated if the narrative structure can be decoded based on functional connectivity information acquired while participants are watching short film animations. These films were divided into an early (exposition and complication) and a later part (climax and resolution) by independent raters, and fMRI data during film watching were split into the two parts accordingly. Each of the splits was transformed into a functional connectivity matrix, and we tested whether the temporal structure (i.e., early, or later part) can be decoded based on the connectivity information using representational similarity and multivariate classification analyses. We could successfully decode the temporal structure of the narratives in both analyses: That is, irrespective of the contents, early and later parts of narratives had differential connectivity patterns from each other. Interestingly, the temporal structure decoding was also successful even when the same analyses were performed “across participants”. In a subsequent analysis, we found that the narrative structure information was predominantly represented in the visual, fronto-parietal, default mode networks. Our findings show that network-level interactions in the brain support representation of narrative structure independent from contents of narratives and individual difference in functional connectivity.

<br>

Keywords: narrative perception, functional connectivity, multivariate pattern analysis, fMRI

## Files
- aniFCnet_results.Rmd : 데이터 분석 및 시각화를 위한 R MarkDown 소스 코드
- aniFC_sFC_analysis.ipynb : 다변량 패턴 분석을 위한 코드
- aniFCnet_results.html : 분석 코드 및 결과. 다운로드 후 확인 가능
- data : raw data, 비어있음.
- py_output : mvpa 결과, 비어있음.
- KSCBP2022.aniFC_ppt.thk.pdf : 인지및생물 2022 학술대회 발표 자료

## License

```
MIT License

Copyright (c) 2022 Kim, Taehoon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
