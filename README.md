#
## LLM 모델(EXAONE-3.5)를 활용한 온 디바이스 앱 개발


### 목 차


### **1장. 안드로이드 앱 개발 도구 및 버전**

- 안드로이드 앱 개발 필수 도구 소개
- Android Studio 최신 버전 소개 (예: Android Studio Narwhal 2025.1.1 이상)
- Jetpack Compose 1.6 및 Kotlin을 활용한 UI 개발 환경 소개
- 안드로이드 NDK 개요 및 사용 버전 설명 (예: NDK 27.0 이상)

### **2장. 안드로이드 앱 개발 환경 설정**

- 개발 환경 필수 요소 설치 방법
- Android Studio 프로젝트 구성 및 설정
- Gradle 설정 및 버전 관리
- AVD 및 실기기에서 앱 테스트 환경 설정

### **3장. Huggingface 오픈소스 플랫폼과 EXAONE-3.5**

- Huggingface 플랫폼 이해하기 
- EXAONE-3.5모델 개요 및 특징
- GGUF포맷 소개 및 장점 
- GGUF모델 파일 다운로드 및 준비 과정

### **4장. llama.cpp 소개 및 활용 방법**

- llama.cpp 프로젝트 개요 및 특징
- llama.cpp 프로젝트 빌드 과정(CMake 활용 및 JNI 설정 등)
- Android NDK와 llama.cpp의 연동 과정 및 주의사항
- llama.cpp 빌드 시 자주 발생하는 문제점 및 해결법

### **5장. 앱 내에서 LLM 모델 활용하기**

- JNI를 활용한 Kotlin과 C++ 네이티브 코드 연동 구조
- LLM 모델 로딩 및 초기화 과정
- 모델 추론(inference) 및 데이터 흐
- 안드로이드에서 효율적인 모델 메모리 관리 전략

### **6장.** **LLM AI 앱 프로젝트** 

- EXAONE-3.5 에뮬레이터 CLI 실행  
- llama.cpp 연동을 위한 브릿지 모듈 제작(LlamaBridge 구현)
- Jetpack Compose UI 구현
- 중급 개발자를 위한 성능 최적화 팁 및 고려 사항
