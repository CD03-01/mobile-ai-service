# 🚀 드라이브 스루를 위한 온디바이스 수어 인식 앱 개발

## 🧑‍💻 멤버 소개

202002529 이어진  
202202556 김도현  
202202593 박채연

## 📌 프로젝트 소개

드라이브 스루 환경에서는 음성 기반 주문 시스템이 일반적이지만, 이는 청각장애인에게 큰 불편을 초래한다. 본 프로젝트는 이러한 소통의 장벽을 해소하고자, 수어 인식 및 음성 인식 기능을 결합한 양방향 커뮤니케이션 앱을 개발하는 것을 목표로 한다.

사용자가 수어로 주문을 하면, 앱이 이를 인식하여 의미 있는 텍스트로 변환해 점원에게 전달하고, 점원이 말로 응답하면 앱이 음성을 인식해 텍스트 형태로 사용자에게 출력한다. 이 모든 기능은 인터넷 없이도 작동 가능한 온디바이스 AI 기반 Android 애플리케이션으로 구현된다.

## 🎯 프로젝트 목표

1. **수어 인식 기능 구현**
   - 사용자의 손 제스처(수어)를 인식하여 텍스트로 변환
   - MediaPipe 기반 손 키포인트 추출 및 LSTM 기반 수어 분류 모델 적용

2. **음성 인식 기능 구현**
   - 점원의 음성 응답을 실시간으로 인식하고 텍스트로 출력
   - 음성 인식 엔진을 활용한 오프라인 음성-텍스트 변환 구현

3. **온디바이스 환경에서의 실시간 처리**
   - TFLite 기반 경량 모델을 활용해 인터넷 없이도 인식이 가능한 앱 개발
   - 네트워크 지연 없이 빠른 응답 제공

4. **양방향 UI/UX 설계**
   - 청각장애인 사용자와 점원이 서로 이해할 수 있도록 직관적이고 접근성 높은 UI 구성
   - 주문 흐름에 최적화된 화면 설계

5. **포용적 기술 개발**
   - 드라이브 스루와 같은 음성 중심 환경에서도 청각장애인이 불편 없이 주문할 수 있는 기술 제공
   - 향후 다양한 언어와 수어 단어로 확장 가능하도록 구조 설계

## 활동 기록  

| 주차  | 활동 개요               | 발표 URL | 깃 PR 링크 |
|------|----------------------|---------|------------------|
| 1주차 | 디자인 개요서 작성 | [유튜브 링크](https://youtu.be/k6VoF2thGbg) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/1) |
| 2주차 | 문제점 목록 작성 | [유튜브 링크](https://youtu.be/iseAybqoh64) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/2) |
| 3주차 | 브레인스토밍 결과 작성 | [유튜브 링크](https://youtu.be/8QuSFgxh-No) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/4) |
| 4주차 | 문제정의서 작성 | [유튜브 링크](https://www.youtube.com/watch?v=qooUvmYUQIk) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/6) |
| 5-6주차 | 유스케이스 명세서 작성 | [유튜브 링크](https://www.youtube.com/watch?v=jPpd5OYzP-Q) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/7) |
| 7-8주차 | 시퀀스 다이어그램 작성 | [유튜브 링크](https://www.youtube.com/watch?v=7SPE0kdX9PE) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/8) |
| 11주차 | 테스트 계획서 작성 | [유튜브 링크](https://www.youtube.com/watch?v=7APJIi2yUNo) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/9) |
| 12-13주차 | 테스트 결과서 작성 + 최종 발표 | [유튜브 링크](https://www.youtube.com/watch?v=yn-kv_r6_tI) | [PR 링크](https://github.com/CD03-01/mobile-ai-service/pull/10) |
