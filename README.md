# Brain-MRI-segmentation
Brain MRI images together with manual FLAIR abnormality segmentation masks

# NGO ROI(ROAS) Direct 광고대비 후원금액 예측
![roas](https://user-images.githubusercontent.com/61241244/123992245-6ab77900-da06-11eb-89a4-4c25758b6d2c.png)

# 1. 목적
### 미디어 지표인 SPOT와 Imps 대비 DRTV 후원금 모금 실적간의 상관관계 분석 ::
![ngo](https://user-images.githubusercontent.com/61241244/123994059-f978c580-da07-11eb-872d-968698296ec9.PNG)
### NGO기관 'S'기관의 후원광고 실적 분석 및 예측 ::
![ngo_01](https://user-images.githubusercontent.com/61241244/123988536-119a1600-da03-11eb-97cf-b27c74ce8f75.JPG)
# 2. 로드맵 ::
### 후원예측 분석 로드맵
 ![ngo_02](https://user-images.githubusercontent.com/61241244/123993988-e7972280-da07-11eb-973c-5e9ec8c8e61c.JPG)
# 3. 용어
- 1) Inbound_Calls : 후원문의전화수, 단위-건
- 2) Reg Donour : 정기후원수, 단위-건
- 3) CV_R : 후원전환율, 단위-%
- 4) Cost : 부가세포함광고비, 단위:천원
- 5) RD Amount : 첫달정기후원금액, 단위-천원
- 6) ROI : 광고비대비 정기후원모금비율
- 7) CPR : 문의전화 1콜 당 비용, 단위-천원
- 8) CPD : 정기후원 1건 개발 비용, 단위-천원
- 9) CPM : 시청자 1천명 개발 비용, 단위-천원
<BR>
# 3. 본론
### 시간대별 시청자수, ROI, 인바운드콜
![월별 시간대별](https://user-images.githubusercontent.com/61241244/123995940-c7686300-da09-11eb-8cd0-9ec2f9ee8a0b.png)
### 채널별 시청자수, ROI, 인바운드콜
![채널별](https://user-images.githubusercontent.com/61241244/123997026-e7e4ed00-da0a-11eb-9aad-4b70344abee5.png)
### 주요특성 상관계수
![특성](https://user-images.githubusercontent.com/61241244/124006375-22538780-da15-11eb-8740-4887bdb56325.PNG)
### 컬럼별 상관계수
![컬럼별상관관계](https://user-images.githubusercontent.com/61241244/124003392-d7844080-da11-11eb-8090-96a435bdb6db.PNG)
### 예상광고비대비 ROI[RED], 후원금액 예측커브[BLUE]
![theend](https://user-images.githubusercontent.com/61241244/124005707-59756900-da14-11eb-8f01-771fcf65b45e.PNG)
### 결론
- 광고량으로 인바운드 콜을 예측하기 위해 광고노출량(시청자수)외 커버리지(Reach), 연령별 변수 추가 필요
- 50대, 60대 남성의 도달자수가 예측력을 높이는 데 중요한 특성
- Reach 1+와 Reach3+ 등 단순노출 외 광고의 커버리지를 반영 -> 채널조합에 따른 변수를 포함
- 모델을 적용하여 예산(일평균) 대비 예상 ROI와 예상 후원금 시뮬레이션
    - 예산에 따른 예상후원금은 3개의 군집으로 시뮬레이션되는 것으로 보임
    - 채널(지상파그룹, 유료채널, 종편그룹)의 비중에 따라 시뮬레이션 커브가 달라지는 것으로 판단됨
- 추후 전체채널에 대해서 분류모델을 적용하여 적정채널 조합을 제시하는 모델로 발전 가능성 높음
