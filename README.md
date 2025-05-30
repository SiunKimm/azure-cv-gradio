# Azure Custom Vision Object Detection with Gradio

이 프로젝트는 Microsoft Azure의 Custom Vision 서비스와 Gradio를 이용하여 **웹 기반의 이미지 객체 탐지 인터페이스**를 제공합니다.
이미지를 업로드하면 Azure의 학습된 Custom Vision 모델을 통해 객체를 인식하고, 결과 이미지를 시각화하여 반환합니다.

---

## 📦 주요 기술 스택
- **Azure Custom Vision**: 사전 학습된 또는 사용자가 학습시킨 객체 탐지 모델 제공
- **Gradio**: 인터랙티브한 웹 인터페이스 제공
- **Python (Pillow, NumPy, Matplotlib)**: 이미지 처리 및 시각화
- **APIKey 인증**: `msrest.authentication.ApiKeyCredentials` 사용
