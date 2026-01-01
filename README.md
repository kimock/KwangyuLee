# Hello
이관규입니다

## 💡 Project


### [Mass Designer](https://github.com/kimock/MassDesigner/tree/main)


건축 설계 프로젝트 [2025.03.03 ~ 2025.06.15]

- Building-GAN 논문을 기반으로 구현 (https://github.com/AutodeskAILab/Building-GAN)
- AutoDesk 120,000개의 프로그램 데이터, 복셀 데이터 사용
- 프로그램 데이터를 복셀로 변환하는 GNN 모델 구현
- 프로그램 데이터를 LLM 파인튜닝으로 텍스트 기반 생성이 가능한 파이프라인
- 기획 설계 단계에서 각종 설계안 생성 및 검토에 활용 가능


### [ArtClassficiation](https://github.com/ckyumini/ArtClassficiation)

심층신경망개론 [2024.10.01 ~ 2024.12.10]

- EfficientFormer를 활용한 화풍 분류 모델
- [Collections of Paintings from 50 Artists](https://www.kaggle.com/code/paultimothymooney/collections-of-paintings-from-50-artists/notebook)를 활용해 태스크 수행
- run length feature를 얕은 신경망 처리하여 추가로 임베딩
- 다양한 화풍 분석에 활용 가능




### 질병네트워크 분석

![데마_최종 발표](https://github.com/user-attachments/assets/acb32cbd-acc3-4cdc-867b-8b676785ec07)

데이터 마이닝 [2024.9.15 ~ 2024.12.13]

- 질병네트워크 그래프를 활용한 네트워크 분석
- 국민건강보험공단 진료내역정보를 활용
- 코호트 분석법 Ords Ratio를 통해 엣지를 형성
- Louvain Algorithm을 통해 클러스터링 수행

### [He is my manger](https://github.com/kimock/He-is-my-manager)

토이 프로젝트 [2025.12.20 ~ 2025.12.28]

- GPT-4o를 활용한 주식 분석 에이전트
- 매일 한국 주식 시장이 마감 직전(15:00 KST), 관심 종목의 차트와 최신 뉴스를 분석하여 매수/매도 전략 리포트를 이메일로 발송
- 기술적 분석(MACD, RSI, 볼린저 밴드(Bollinger Bands), OBV)과 실시간 뉴스 RAG 정보를 종합하여 매매 등급 산출
- 별도의 서버 없이 GitHub Actions를 통해 평일 오후 3시에 자동으로 실행
- 분석 결과(텍스트)와 차트(이미지)를 HTML 템플릿으로 렌더링하여 메일 전송

### 깃허브 리포지토리-네트워크 분석

![Untitled](https://github.com/user-attachments/assets/8ffd593b-726a-47ab-9a0e-b353b50f5d27)

토이 프로젝트 [2024.12.20 ~ 2024.12.31]

- 깃허브 Transformer 리포지토리를 중심으로 Contributer와 네트워크 그래프 제작
- 깃허브 API를 활용하여 크롤링
- 단순한 빈도수 Edge 활용
- Forced Atlas 3D를 통해 3차원 매핑


### GRUGNN 모델 활용



토이 프로젝트 [2025.01.03 ~ 2025.01.15]

- Building-GNN 논문을 기반으로 구현
- 간단한 복셀 데이터를 학습하고 마스킹 구간 예측
