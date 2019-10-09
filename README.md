# ChatbotProject
## 2019 서울 인공지능 챗봇톤
### 갈릭디핑소스 팀원: 임성학, 이민진, 이상균, 이준기
![image](https://user-images.githubusercontent.com/54702684/66451860-344f0300-ea99-11e9-9266-90083f7e23f3.png)

1. 기획의도 : 미취업 청년들을 대상으로 텔레그램 메신저를 통해 청년수당에 관한 A부터 Z까지 모든 것을 알려주는 챗봇
2. 주요 기능 : 청년수당 개념 전달, 미래를 준비하는 미취업 청년들이 청년수당을 좀더 쉽게 접근하고 수령할 수 있게 도움
3. 페르소나
   - 차가운 도시 남자지만 청년에게는 따뜻한 조(助:돕다)비서
   - <도깨비>의 김비서, <내부자들>의 조상무를 연기한 조우진
   - 청년수당에 대한 답변은 따뜻한 김비서, 인식하지 못 한 질문은 냉철한 김비서
4. 시나리오
![image](https://user-images.githubusercontent.com/54702684/66452730-95c4a100-ea9c-11e9-889b-263560ed83c6.png)
   - 흐름 : 인사 및 청년수당 안내 → 자격요건 → 신청방법 → 선정기준 → 사용방법 → 혜택종료 → 마무리
   - 특별 메시지 : 조비서의 응원(조비서가 청년을 응원하는 따뜻한 메시지를 전달)
5. 사용 라이브러리
   - urllib.request, flask, openpyxl, numpy, ibm_watson, ibm_cloud_sdk_core.authenticators, requests, os 
