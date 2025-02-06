# 2024_1_sejong_web_project
이활동은 이아현, 박수진, 신찬영, 이지민, 황상훈이 참여하엿습니다.
# 세종대학교 집현캠퍼스 개선 웹 서비스 개발

## 1. 프로젝트 개요

본 프로젝트는 기존 세종대학교 집현캠퍼스 웹 서비스를 개선하여 사용자 편의성을 높이는 것을 목표로 다. 얼굴 보안 인식 로그인 시스템, 강의 요약 기능, 기념일에 따라 바뀌는 로고 및 다양한 배너를 제공하여 사용자에게 더 편리하고 유용한 기능을 제공할 수 있다.

## 2. 팀원 및 역할 분담

| 팀원    | 학번       | 학과                      | 역할                                                                                                                                                                                                                |
| :------ | :-------- | :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 이아현  | 21012019 | 인공지능데이터사이언스학과  | **팀장**, 강의 영상 텍스트 변환(STT) 및 요약 기능 구현, KoBART 모델 fine-tuning, Django를 이용한 요약 기능 웹 구현                                                                                                                                 |
| 신찬영  | 23012094 | 인공지능데이터사이언스학과  | CNN, Siam Network, MobileNet,  YOLO, harcascade 학습, 얼굴 인식 모델 구축, Django를 이용한 얼굴 인식 웹앱 시스템 구현                                                                                   |
| 이지민  | 23012127 | 인공지능데이터사이언스학과 | CNN, Siamese Network 학습, Dlib, FaceNet 활용, confusion matrix 등 학습, 얼굴 인식 로그인 프로그램 제작, 모델 배포                                                  |
| 박수진  | 21011998 | 인공지능데이터사이언스학과  | STT 모델 학습 (Whisper, Google Cloud Speech-to-Text, Speech Recognition), 웹 페이지 UI 디자인 (Figma), HTML/CSS 구현, Django 연동                                                           |
| 황상훈  | 23012120 | 인공지능데이터사이언스학과  | 포토샵 학습, 기념일 로고 및 배너 디자인,  HTML/CSS, Django 학습, 강의 페이지 및 교수님 파일 업로드 페이지 제작                                            |

## 3. 학습 목표

*   얼굴 인식 로그인 시스템 구축 (Siam Network, MobileNet 등 학습)
*   새로운 집현 캠퍼스 로고 및 배너 디자인 (Photoshop 기능 학습)
*   웹 페이지 제작 (Django, HTML, CSS 학습)
*   강의 요약 기능 구현 (STT, KoBERT, KoBART 학습, AI Hub 데이터셋 fine-tuning)

## 4. 사용 기술

*   **얼굴 인식:**
    *   Siam Network
    *   YOLO
    *   harcascade
    *   facenet
    *   MobileNet
    *   Dlib
*   **이미지 처리:**
    *   Python
    *   PyTorch
    *   OpenCV
*   **디자인:**
    *   Photoshop
    *   Figma
    *   Canva
* **웹 개발:**
    * Django
    * HTML
    * CSS
    * Visual Studio Code
*   **음성 처리:**
    *   MoviePy
* **STT(Speech-to-Text):**
    *   Whisper
    *   Google Cloud Speech-to-Text
    *    Speech Recognition
*   **텍스트 요약:**
    *   KoBERT
    *   KoBART
    *   AI Hub 데이터셋
* **기타**
    *   hugging face
    *   DALL.E2

## 5. 회차별 학습 내용 및 개발 내용

| 회차 | 학습 및 개발 내용                                                                                                                                                                                                                                                                                                         |
| ---: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|    1 | - Django 웹에 강의 영상 업로드 및 음성 추출 기능 구현- MobileNet 학습 및 구현, 얼굴 분류 학습- GAN 학습, DALL.E2 활용- MoviePy, Django 학습                                                |
|    2 | - harcascade 학습 및 구현- 포토샵 기능 학습 (이미지 수정)- STT 모델 및 라이브러리 학습 (Whisper, Speech Recognition, Google Cloud Speech-to-Text)- Speech Recognition을 이용한 텍스트 추출                                                        |
|    3 | - Siam Network, CNN 학습, 기본 구조 구축- 기념일 로고 제작 (포토샵)- Figma 학습, 집현 캠퍼스 메인 페이지 UI 스케치 및 디자인- Django 데이터베이스, forms 학습, STT 웹 구현                   |
|    4 | - YOLO 학습, 커스텀 학습, 얼굴 추출- Dlib 활용, FC 학습- 집현 캠퍼스 UI 및 배너 디자인- Figma 기능 학습, Auto Layout 적용- Transformer 모델 (BERT, GPT) 학습, KoBERTSum 모델 분석        |
|    5 | - MobileNet + Siam Network 모델 하이퍼파라미터 조정, 데이터셋 재구축, 전이 학습- 웹캠 이미지 적용, 필드 테스트- HTML 학습, 웹페이지 제작, 세부 페이지 UI 제작- Constraint 적용, 로그인 페이지 UI 및 프로토타입 제작- KoBART 학습 (BART 아키텍처, KoBART 요약 코드)         |
|    6 | - Confusion matrix 학습, 모델 평가 (1종 오류 확인)- Django 학습, 웹페이지 제작- HTML, CSS 학습, 메인 페이지 header, '나의강의', '나의과제', '인기키워드' 부분 제작- KoBART summarization 모델 코드 학습 (hugging face kobart-base-v1)                                    |
|    7 | - HTML, 웹, 네트워크, 인터넷 학습- facenet 학습, pre-train model 변경, 오차함수 수정- HTML 태그, CSS 속성 학습, Django 라우팅 (urls.py, views.py)- HTML, CSS 실습, 메인 페이지 '공지사항', '이용안내', footer 제작, 얼굴인식 로그인 페이지 구현- KoBART fine-tuning (aihub 데이터), 모델 저장 및 로드, generate 함수로 요약         |
|    8 | - Django 학습- 모델 하이퍼파라미터 조정, 최적값 탐색- Figma, 웹페이지 소스 코드 간소화, 강의 페이지 상단 제작- HTML frame 요소, CSS (classes and IDs) 학습, 세종포탈 로그인 페이지, 메인 페이지 일부 구현- KoBART summarization fine-tuning (기술 과학 요약 데이터 추가), 모델 로드, 강의 텍스트 요약                                        |
|    9 | - HTML, Django 활용, 얼굴인식 보안 웹앱 제작- 집현 캠퍼스 강의 페이지 HTML, CSS 제작 (function12, Figma 활용)- HTML form 요소, CSS (grid, 스크롤바) 학습, 로그인 후 메인 페이지 완성, 기능 보완- KoBART summarization 요약 기능 Django 구현 (tokenizer, 로컬 저장, 사용자에게 제공)        |
|   10 | - 얼굴인식 보안 웹앱 재구축- 교수님 파일 업로드 HTML 제작- Django 학습, HTML/CSS 코드 Django로 이동- 데이터베이스 필드타입 수정, summary 필드 추가, 요약 텍스트 사용자에게 제공                                    |

## 6. 결과물

### 6.1. 웹 서비스 기능

*   **얼굴 인식 로그인:**
    *   Siam Network 기반 모델, 사진 부정행위 방지 (YOLO)
*   **강의 요약:**
    *   STT (Google Speech Recognition API)
    *   KoBART 기반 요약 (AI Hub 데이터셋 fine-tuning)
*   **기념일별 로고 및 배너:**
    *   DALL.E2, Photoshop, Canva 활용

### 6.2. 스크린샷

#### 로그인 전 메인 페이지
![image](https://github.com/user-attachments/assets/ee220fc7-f001-49d9-a576-af2f5e0df462)


#### 얼굴 인식 로그인 페이지
![image](https://github.com/user-attachments/assets/14d15381-58f8-4735-9729-e40b2507d9bb)


#### 부정행위 감지
![image](https://github.com/user-attachments/assets/9984cfdc-65d6-4315-a0d4-b304cad23152)

#### 로그인 후 메인 페이지
![image](https://github.com/user-attachments/assets/87e9d2fa-e5d0-4029-b8d8-a53240dae213)


#### 교수님 영상 업로드 페이지
![image](https://github.com/user-attachments/assets/b026339a-670e-48f6-ae5a-e225504c6b12)


#### 강의 영상 요약 페이지
![image](https://github.com/user-attachments/assets/6bfd9368-1419-45a2-a93d-60657a01ff69)


### 6.3. 로고 및 배너 예시
#### 로고
|                                                                |                                                                 |                                                                |
| :----------------------------------------------------------------: | :-----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![image](https://github.com/user-attachments/assets/50814ae5-93ed-4fbb-b654-5a555594c946)
청룡의 해  |     ![image](https://github.com/user-attachments/assets/3dcc77bc-e824-40e3-a82a-15e274c49aa4)
 학기 시작      |       ![image](https://github.com/user-attachments/assets/ec3a404b-a8b0-4ec0-b71a-65013e187f79)
 설날        |
|      ![image](https://github.com/user-attachments/assets/7915edfd-3fd9-46a9-b7d2-a52bcaf2474a)
 삼일절       |    ![image](https://github.com/user-attachments/assets/ed673796-0ef2-4499-aa58-13c02d133fac)
 어린이날     |     ![image](https://github.com/user-attachments/assets/c2a5ae35-410c-428b-b439-1095ba0cb6f2)
 현충일     |
|       ![image](https://github.com/user-attachments/assets/b4ae729a-ab8c-4fba-9cdf-4dff6c742804)
추석         |      ![image](https://github.com/user-attachments/assets/db65b84d-99be-4ec9-bc91-8b5b6d812522)
 개천절       |      ![image](https://github.com/user-attachments/assets/40da8743-d60d-416b-9878-25cc3e4bc97b)
  한글날       |
|      ![image](https://github.com/user-attachments/assets/ef67324b-3b13-482b-8696-23da73d8e116)
크리스마스     |                                                                     |

#### 배너
|                                                     |                                                   |
| :-------------------------------------------------: | :------------------------------------------------: |
|  ![image](https://github.com/user-attachments/assets/2623ee42-bc4e-4370-9728-dd719bbf6271)
   |   ![image](https://github.com/user-attachments/assets/c60b1ead-473d-40e3-bee1-80a2e0d8b833)
  |
| ![image](https://github.com/user-attachments/assets/aba33121-74bd-4f20-9bf3-2f1be8a4e5fb)
 | ![image](https://github.com/user-attachments/assets/dda8afc9-4c9d-4034-a9ce-0085ac63d89c)
 |
|     ![image](https://github.com/user-attachments/assets/ef4a621c-5147-43ed-8df9-0c81d6022fbb)
     |      ![image](https://github.com/user-attachments/assets/86d0ef13-2e41-47dc-8f1e-c6cef84c15b5)
    |

## 7. 기대 효과

*   비밀번호 입력 없이 얼굴 인식으로 편리한 로그인
*   강의 요약 기능으로 학습 효율 증대
*   기념일별 로고 및 배너로 시각적 재미 제공, 학교 소식 전달

## 8. 향후 계획 (Optional)
* STT 한국어 인식률 개선
* 강의 요약 기능 고도화
* UI/UX 개선

## 9. 참고 자료 (Optional)
*   [MoviePy documentation](https://zulko.github.io/moviepy/)
*   [SpeechRecognition documentation](https://pypi.org/project/SpeechRecognition/)
*   [KoBART GitHub](https://github.com/SKT-Brain/KoBART)
* [AI Hub 데이터셋](https://www.aihub.or.kr/)

---

**Note:**

*   `your-repo` 와 `your-project` 부분을 실제 GitHub repository와 프로젝트 이름으로 변경해주세요.
*   스크린샷 파일들을 `images` 폴더에 저장하고, Markdown 파일에서 상대 경로로 참조해주세요 (예: `images/main_page.png`).
*   필요에 따라 섹션 (예: 향후 계획, 참고 자료)을 추가하거나 수정할 수 있습니다.
*  코드 예시, 이미지, 영상등을 추가하면 더 가독성이 좋아집니다.
