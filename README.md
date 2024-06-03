# DB_Yeongcheon
KHUDA_5th
1. 프로젝트 소개
   감성분석을 기반으로 한 영천시 관광지 추천 시스템
   
2. 데이터 전처리
   관광지별 키워드 라벨링
  
3. NLP(감성분석) 기반 추천점수 도출
   사용자 메모를 형태소 분석하여 불용어 제거 및 키워드 추출
   관광지 키워드에 TF-IDF 벡터화 수행
   사용자 메모 키워드와 코사인 유사도 계산, 이를 바탕으로 추천점수 도출
   
4. 거리 기반 추천점수 도출 및 클러스터링
   관광지들을 지도상에서 클러스터링
   현재 사용자 위치와의 거리 계산, 이를 바탕으로 추천점수 도출
   
5. 최종 서비스
   NLP 기반 추천점수와 거리 기반 추천점수를 결합하여 최종 추천점수 도출
   사용자의 현재 위치와 선호하는 거리 정도, 여행 취향에 대한 메모를 입력하면 추천 점수가 가장 높은 관광지 클러스터 리스트 출력

6. 기대효과
   개인 관심사와 위치 기반 관광지 추천을 통한 사용자 여행 만족도 향상
   다양한 관광지 발견 및 활성화를 통해 지역 상권 및 숙박업소에 긍정적 영향 부여
   데이터의 지속적인 수집으로 더 개선된 알고리즘을 통한 관광지 추천 
