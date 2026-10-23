<div align="center">

# Git Exercise

**이성민 (Sungmin Lee)** · Physical AI Developer

아이디어를 직접 실행되는 프로그램으로 만들고, 배포해서 누구나 써 볼 수 있게 하고,<br>
만든 과정을 학습 노트로 기록합니다.

<a href="mailto:leesm3528@gmail.com"><img src="https://img.shields.io/badge/Email-leesm3528@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/K--Digital-피지컬%20AI%20과정-ffd166?style=flat-square"/>
<img src="https://img.shields.io/badge/Deployed-8%20services-2ea44f?style=flat-square"/>

</div>

---

## About Me

- **K-Digital 피지컬 AI 과정**(트레이닝: ETEDU)에서 Python, 컴퓨터 비전, 웹, Git을 배우고 있습니다.
- 웹캠과 AI 모델(YOLO, MediaPipe, Teachable Machine)로 **현실 세계를 인식하는 프로그램**을 주로 만듭니다.
- **아두이노 우노**로 직접 회로를 꽂고 코드를 올려서 버튼·LED·센서를 다루는 **피지컬 컴퓨팅**을 배우고 있습니다.
- **XIAO ESP32-S3**로 센서·LED·카메라를 Wi-Fi, 클라우드(Supabase), BLE로 스마트폰과 연결하는 **IoT**를 만들고 있습니다.
- 만든 프로그램은 **GitHub Pages와 Vercel로 배포**해서 링크 하나로 바로 써 볼 수 있게 합니다.
- 주요 프로젝트마다 **작업 기록과 학습 노트**를 남깁니다. 무엇을 했는지와 함께 왜 그렇게 했는지도 적습니다.

---

## Projects

### Featured — 무인도 생존 교육 시스템

미래의 내가 설계한 '시스템 창'이 생존 퀘스트를 냅니다. 레벨업하면 구조 헬기가 보급품을 떨어뜨리고,
표류자를 구할지 경계할지에 대한 선택이 탈출 엔딩을 바꿉니다.

<img src="assets/demo.gif" width="360" alt="무인도 생존 교육 시스템 시연: 정답 → 레벨업 헬기 보급 → 표류자 구조 → 버프">

| | |
|---|---|
| **규모** | 퀘스트 100개 · 표류자 5명 · 엔딩 3종 · 레벨별 EXP 곡선 |
| **구현** | Python tkinter 버전 + Flask 웹 버전 (정답 판정은 서버에서만 수행) |
| **기술** | Python · tkinter · Flask · JavaScript · JSON |
| **링크** | [Live Demo](https://leesm3528-netizen.github.io/island-survival-system/) · [Repository](https://github.com/leesm3528-netizen/island-survival-system) · [학습 정리](https://github.com/leesm3528-netizen/island-survival-system/blob/main/STUDY_NOTES.md) |

### Computer Vision · Physical AI

| 프로젝트 | 설명 | 기술 | 링크 |
|---|---|---|---|
| **MediaPipe Webcam** | 손 랜드마크 21점 · 제스처 · 얼굴 인식 실시간 데모, 나만의 제스처를 수집하고 학습시키는 스튜디오, 브라우저 데모 | Python · OpenCV · MediaPipe · tkinter · JS | [Repo](https://github.com/leesm3528-netizen/mediapipe-webcam) · [Live](https://leesm3528-netizen.github.io/mediapipe-webcam/) |
| **웹캠 뱀게임** | 손짓·몸짓을 Teachable Machine 이미지 모델로 분류(상·하·좌·우·정지)해서 뱀을 조종하는 게임 | JS · TensorFlow.js · Teachable Machine | [Repo](https://github.com/leesm3528-netizen/snake) · [Live](https://leesm3528-netizen.github.io/snake/) |
| **YOLO26 Vision** | 웹캠 영상으로 객체 탐지와 인스턴스 세그멘테이션을 실시간 실행, 개발 환경 세팅부터 정리한 강의노트 | Python · Ultralytics YOLO26 · OpenCV | [Repo](https://github.com/leesm3528-netizen/vision) |

### Physical Computing · Arduino

<img src="https://raw.githubusercontent.com/leesm3528-netizen/arduino-uno-lab/main/assets/03-toggle-demo.gif" width="200" alt="아두이노 신호등: 버튼을 누르면 신호등이 꺼지고 다시 켜지는 시연">

| 프로젝트 | 설명 | 기술 | 링크 |
|---|---|---|---|
| **Arduino Uno Lab** | LED 깜빡이기부터 디바운싱·인터럽트·PWM·네오픽셀·소리 센서까지 익히고, 버튼으로 켜고 끄는 **실물 신호등**과 **7세그먼트 숫자 카운터**를 브레드보드에 만든 학습 기록 | C++ · Arduino Uno · arduino-cli · Tinkercad · Wokwi | [Repo](https://github.com/leesm3528-netizen/arduino-uno-lab) · [학습 정리](https://github.com/leesm3528-netizen/arduino-uno-lab/blob/main/STUDY_NOTES.md) |
| **XIAO ESP32-S3 Lab** | 터치센서·LED를 **같은 Wi-Fi 웹서버 → Supabase 원격 제어 → 카메라 MJPEG 스트리밍(3명 동시 시청) → AP 모드 → BLE** 다섯 가지 방식으로 스마트폰과 연결한 IoT 학습 기록 | C++ · ESP32-S3 · Supabase · Web Bluetooth · FreeRTOS | [Repo](https://github.com/leesm3528-netizen/xiao-esp32s3-lab) · [Live](https://leesm3528-netizen.github.io/xiao-dashboard/) · [학습 정리](https://github.com/leesm3528-netizen/xiao-esp32s3-lab/blob/main/STUDY_NOTES.md) |

### Web Service · Full Stack

| 프로젝트 | 설명 | 기술 | 링크 |
|---|---|---|---|
| **아두몰 (Arduino Shop)** | 아두이노 부품 쇼핑몰: 상품 검색·정렬, 장바구니, 회원가입, 토스페이먼츠 테스트 결제까지 구현한 풀스택 서비스 | Next.js · TypeScript · Supabase · Vercel | [Repo](https://github.com/leesm3528-netizen/arduino-shop) · [Live](https://arduino-shop-gamma.vercel.app) |
| **드래곤볼 PC 연구소** | 다나와 부품 최저가를 수집하고, 예산 안에서 소켓·파워 호환성을 검사해 가성비 조합을 자동 추천 | Python · JS · Vercel | [Repo](https://github.com/leesm3528-netizen/dragonball-pc) · [Live](https://dragonball-pc.vercel.app) |
| **연애 사주** | 사주·MBTI·혈액형·체격으로 솔로/커플 궁합을 계산하고, 직접 그린 SVG 캐릭터와 점수 애니메이션으로 결과를 보여 줌 | HTML · CSS · JS · Python | [Repo](https://github.com/leesm3528-netizen/saju-love-match) · [Live](https://leesm3528-netizen.github.io/saju-love-match/) |

### Game

| 프로젝트 | 설명 | 기술 | 링크 |
|---|---|---|---|
| **Neon Pinball** | HTML5 Canvas 하나로 만든 핀볼: 플리퍼, 범퍼, 슬링샷, 드롭 타깃, 배율 레인, 터치 조작 | HTML · Canvas API · Web Audio API | [Repo](https://github.com/leesm3528-netizen/pinball) · [Live](https://leesm3528-netizen.github.io/pinball/) |

---

## Tech Stack

| 구분 | 주력으로 사용 | 사용 경험 있음 |
|---|---|---|
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **AI / Vision** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white) | ![YOLO](https://img.shields.io/badge/YOLO26-111F68?style=flat-square&logo=ultralytics&logoColor=white) ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Teachable Machine](https://img.shields.io/badge/Teachable_Machine-4285F4?style=flat-square&logo=google&logoColor=white) |
| **Backend / Web** | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![tkinter](https://img.shields.io/badge/tkinter-3fa9ff?style=flat-square&logo=python&logoColor=white) | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) |
| **Hardware** | | ![Arduino](https://img.shields.io/badge/Arduino_Uno-00878F?style=flat-square&logo=arduino&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white) ![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Tinkercad](https://img.shields.io/badge/Tinkercad-1477D1?style=flat-square&logo=autodesk&logoColor=white) |
| **Data** | ![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white) ![CSV](https://img.shields.io/badge/CSV-217346?style=flat-square&logo=microsoftexcel&logoColor=white) | |
| **Deploy / Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white) |

---

## Education & Certifications

| 구분 | 과정 | 지원 사업 | 트레이닝 기업 | 기간 |
|---|---|---|---|---|
| 교육 | **피지컬 AI 과정** | 고용노동부 K-Digital Training | **ETEDU** | 2026 ~ 수강 중 |

<!-- 자격증·수상이 생기면 위 표에 한 줄씩 추가하세요 -->

---

## Repositories

| 분류 | 레포지토리 | 배포 |
|---|---|---|
| **Featured** | [island-survival-system](https://github.com/leesm3528-netizen/island-survival-system) | GitHub Pages |
| Vision | [mediapipe-webcam](https://github.com/leesm3528-netizen/mediapipe-webcam) | GitHub Pages |
| Vision | [snake](https://github.com/leesm3528-netizen/snake) | GitHub Pages |
| Vision | [vision](https://github.com/leesm3528-netizen/vision) | 로컬 실행 |
| Physical | [arduino-uno-lab](https://github.com/leesm3528-netizen/arduino-uno-lab) | 실물 보드 (Arduino Uno) |
| Physical | [xiao-esp32s3-lab](https://github.com/leesm3528-netizen/xiao-esp32s3-lab) | 실물 보드 (XIAO ESP32-S3) + GitHub Pages |
| Web | [saju-love-match](https://github.com/leesm3528-netizen/saju-love-match) | GitHub Pages |
| Web | [arduino-shop](https://github.com/leesm3528-netizen/arduino-shop) | Vercel |
| Web | [dragonball-pc](https://github.com/leesm3528-netizen/dragonball-pc) | Vercel |
| Game | [pinball](https://github.com/leesm3528-netizen/pinball) | GitHub Pages |

---

## Collaboration

- **Git 워크플로** — 기능 단위로 커밋하고, 브랜치에서 작업한 변경은 Pull Request로 검토한 뒤 `main`에 합칩니다. 커밋 메시지에는 무엇을 왜 바꿨는지 적습니다.
- **문서로 소통** — 주요 레포에 README, 실행 방법, 작업 기록(WORKLOG / STUDY_NOTES / LEARNING_GUIDE)을 남겨 처음 보는 사람도 바로 따라 할 수 있게 합니다.
- **협업을 고려한 설정** — `.env.example`로 환경 변수를 공유하고, 비밀 키는 커밋하지 않습니다 (`.gitignore` 관리).
- **함께 배우는 동료** — K-Digital 피지컬 AI 과정 동기들과 함께 학습하고 있습니다.

![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Desktop](https://img.shields.io/badge/GitHub_Desktop-8A2BE2?style=flat-square&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

---

## Languages

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=leesm3528-netizen&layout=compact&hide_border=true" height="150"/>

</div>

---

<div align="center">

**Contact** · leesm3528@gmail.com

</div>
