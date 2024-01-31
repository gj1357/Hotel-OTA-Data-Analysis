# Hotel-OTA-Data-Analysis

## **분석 개요**
> 2023년 6월에 OTA를 통해 수집된 호텔 예약 데이터를 분석하여 지역이나 요일, 플랫폼별로 어떤 차이와 패턴을 보이는지에 대해 미니 프로젝트를 수행했습니다.
> 분석 파일 하단의 내용을 ReadMe 파일에 아래와 같이 정리해 보았습니다.

## 해소하고자 하는 가설**
1. 평균 호텔 객실가(ADR)의 범위
2. 요일별 객실 판매량
3. 가격 분포 확인 및 분포 내 90% 지점 확인
4. 지역별 혹은 도시별 객실 판매량
5. 코로나19 엔데믹 선언 이후 국내 호텔 예약 증감 확인
6. 서울 호텔 중 판매량이 가장 높은 호텔 확인
7. OTA 별 호텔 객실 판매 현황, 특징, 판매 트렌드 파악

## 인사이트

### **1. 가격 분포**
* 데이터의 90% 이상이 평균 가격 기준으로 37만원 이하에 치우쳐 있습니다.

* 이는 보다 경제적인 옵션을 선호하는 호텔 예약자들이 대부분이라는 것을 보여줍니다.

* 따라서, 지역 객실 평균 단가를 조사하고 손실 분기점을 넘지 않는 선에서 가격 경쟁력을 확보할 수 있다면, 더 많은 예약과 충성 고객을 확보하면서 호텔 최대 손실인 공실을 막을 수 있을 것으로 보입니다.

### **2. 요일별 예약 현황**
* 요일별 호텔 예약 현황을 보면 목요일, 금요일, 수요일 순서로 숙박 예약하는 사람이 가장 많았습니다.

* 해당 정보를 통해서 주말이 아닌 평일에 호텔을 이용하는 고객들이 많다는 것을 파악할 수 있었습니다.

* 이를 통해, 비즈니스 여행객 또는 주말을 피해 평일에 시간을 내서 여행하는 고객들을 타겟으로 한 상품 판매가 더욱 적극적으로 이루어져야 한다는 인사이트를 얻을 수 있었습니다.

### **3. 지역별 판매 현황**
* 지역별 판매 현황을 보면 강원, 경상, 제주 순으로 객실이 가장 많이 판매되었습니다.

* 특히, 수도권이 아닌 외곽 지역에 대한 여행 수요가 높은 것으로 보아 비즈니스 여행이 아닌 휴양객들의 수요가 더욱 높은 것으로 나타납니다.

> 국내 여행 수요가 해외로 빠지기 시작한 시점에도 불구하고 국내 여행 수요가 아직 유지되는 이유는 다음과 같이 생각해 볼 수 있습니다.
  1. 이전에 계획하고 이미 예약해 놓은 고객들의 국내 여행 수요가 관성적으로 지속되고 있기 때문입니다.
  2. 또한, 해외여행 수요가 높음에도 불구하고 항공권의 가격이 아직 높아서 국내 여행의 수요가 당분간은 지속될 것으로 예상됩니다.


### **4. 부산의 호텔 예약 현황**
* 부산의 경우 판매량은 타지역보다 적지만 수도권 대비 높은 가격으로 판매되었습니다.
* 특히, 오션뷰와 같은 지리적인 이점이 있는 지역에서는 럭셔리 호텔 예약 비중이 상대적으로 높았습니다.
* 럭셔리호텔에 대한 수요가 높은 만큼, 가격 경쟁력을 지니거나 제한된 고객 수요 대비 과도한 경쟁을 방지하기 위해 다른 지역을 물색해 볼 수도 있습니다.

### **5. OTA 예약 현황**
* OTA 예약 현황을 비교했을 때, AGODA, EXPEDIA, YANOLJA, BOOKING, GOODCHOICE 는 서로 유의미한 차이가 없는 예약 현황을 보였습니다.
* 다만, BOOKING.COM과 GOODCHOICE의 경우 판매 객실의 대부분이 수도권보다는 비수도권 호텔이었습니다.
* 따라서, 지방 호텔 판매에 대한 마케팅을 고려할 때 위와 같은 OTA에서 적극적으로 마케팅 활동을 수행해 볼 수 있습니다.

## **향후 방향성**
> 이러한 인사이트를 바탕으로 다음과 같은 향후 방향성을 제시할 수 있습니다.
1. 호텔 업계는 가격 경쟁력을 갖추는 것이 중요한 만큼, 주변 호텔에 대한 데이터 확보가 필요하다. 이를 위해 OTA 데이터를 활용한 분석을 통해 OTA별 특징을 파악하고 개별 전략을 수립해 볼 수 있다. (OTA 예약 현황의 지방 공략 OTA 등의 예시 활용 가능)
2. Occupancy를 측정할 수 있도록 객실 등급(Budget, Mid-Scale, UpScale, Deluxe, Luxury)과 호텔별 총 객실 수에 대해서 세밀하게 분류할 수 있다면 더욱 정밀한 ADR 예측이 가능하다.
3. 고객군을 분리해서 해외 유입 고객, 국내 유입 고객, 연령 등의 다양한 정보를 공유받을 수 있다면 더욱 세밀한 마케팅 전략을 세워볼 수 있다.
4. 평일에 호텔을 이용하는 고객들을 대상으로 한 마케팅 전략을 세우는 것이 고객 확보에 도움이 된다. 비즈니스뿐만 아니라 휴양객을 타겟으로 한 수도권 외 지역 공략이 필요하다. 특히, 부산과 같이 특정 지역적 이점을 가진 곳에서는 Luxury 호텔 시장을 고려해 볼 수 있다.



