# 🤖 AI Model Inference Playground

![Platform](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)


다양한 최신 AI 모델들을 Google Colab에서 즉시 실행해볼 수 있도록 모아둔 저장소입니다.


## 📚 목차 
1. [💬 Large Language Models (LLM)](#-large-language-models-llm)
2. [🎨 Image & Video Generation](#-image--video-generation)
3. [🎙️ Audio & Speech](#-audio--speech)

---

### 💬 Large Language Models (LLM)
> 텍스트 생성, 챗봇, 번역 작업을 위한 모델입니다.

- **Llama-3-8B-Instruct** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![GPU](https://img.shields.io/badge/GPU-T4_Compatible-blue) <br>
  메타(Meta)의 최신 오픈소스 모델입니다. 한국어 튜닝이 적용되어 자연스러운 대화가 가능합니다.

- **Solar-10.7B** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![GPU](https://img.shields.io/badge/GPU-T4_HighRAM-orange) <br>
  Upstage의 고성능 한국어 LLM입니다. RAG 및 긴 문맥 처리에 유리합니다.

- **Gemma-2b-it** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![CPU/GPU](https://img.shields.io/badge/Run-CPU_Possible-green) <br>
  구글의 초경량 모델로, 무료 코랩 환경에서도 매우 빠르게 동작합니다.

---

### 🎨 Image & Video Generation
> 텍스트를 입력받아 이미지나 영상을 생성합니다.

- **Stable Diffusion XL (SDXL)** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![GPU](https://img.shields.io/badge/GPU-V100_%2F_A100-red) <br>
  고해상도 이미지 생성을 위한 최고의 오픈소스 모델입니다. (Fooocus UI 포함)

- **AnimateDiff (Motion Module)** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![GPU](https://img.shields.io/badge/GPU-T4_Compatible-blue) <br>
  기존 이미지를 움직이는 짧은 애니메이션으로 변환합니다.

---

### 🎙️ Audio & Speech
> 음성 인식(STT) 및 음성 합성(TTS) 모델입니다.

- **Whisper-v3-Large** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![Task](https://img.shields.io/badge/Task-STT-yellow) <br>
  OpenAI의 강력한 음성 인식 모델입니다. 유튜브 영상 자막 생성에 유용합니다.

- **RVC (Retrieval-based Voice Conversion)** <br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](링크입력) ![Task](https://img.shields.io/badge/Task-Voice_Changer-purple) <br>
  목소리를 다른 사람의 목소리로 실시간 변환하는 AI 모델입니다.

---

## ⚠️ 사용 가이드 (Usage Guide)

1. **배지 확인**: 각 모델 옆의 `GPU` 배지를 확인하여 본인의 Colab 환경(무료/Pro)에 맞는지 확인하세요.
   - ![Blue](https://img.shields.io/badge/Blue-T4_(Free)-blue) : 무료 계정에서 실행 가능
   - ![Red](https://img.shields.io/badge/Red-A100_(Pro)-red) : Colab Pro 이상의 고사양 GPU 필요
2. **실행**: `Open In Colab` 버튼을 클릭합니다.
3. **런타임 연결**: 상단 메뉴 `런타임` > `런타임 유형 변경`에서 GPU가 올바르게 선택되었는지 확인 후 실행하세요.

---
*Last Update: 2024.05.20*
