# 🔖 My Developer Bookmarks

학습 과정에서 영감을 얻었거나 실무에서 자주 참고하는 유용한 사이트들을 카테고리별로 정리한 저장소입니다.

---

### 📑 INDEX

인덱스를 클릭하면 해당 카테고리로 바로 이동합니다.

<div align="center">
  <a href="#ai"><img src="https://img.shields.io/badge/AI-FF6F61?style=for-the-badge&logo=openai&logoColor=white"/></a>
  <a href="#ps"><img src="https://img.shields.io/badge/PS-0078D4?style=for-the-badge&logo=codeforces&logoColor=white"/></a>
  <a href="#uiux"><img src="https://img.shields.io/badge/UI%2FUX-FFB400?style=for-the-badge&logo=figma&logoColor=white"/></a>
  <a href="#docs"><img src="https://img.shields.io/badge/DOCS-512BD4?style=for-the-badge&logo=googledocs&logoColor=white"/></a>
  <a href="#front"><img src="https://img.shields.io/badge/FRONT-61DAFB?style=for-the-badge&logo=react&logoColor=black"/></a>
  <a href="#back"><img src="https://img.shields.io/badge/BACK-339933?style=for-the-badge&logo=node.js&logoColor=white"/></a>
  <a href="#devops"><img src="https://img.shields.io/badge/INFRA%20%26%20TEST-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/></a>
  <a href="#deploy"><img src="https://img.shields.io/badge/DEPLOY-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="#data"><img src="https://img.shields.io/badge/DATA-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/></a>
  <a href="#news"><img src="https://img.shields.io/badge/NEWS-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
</div>

<br />

---

## <a name="ai"></a>🤖 AI & Model Arena

> 최신 AI 모델, 성능 비교 및 생성 도구

| Name | Description | Link |
| :--- | :--- | :--- |
| **Kimi K3** | 2.8조 파라미터, 네이티브 비전, 100만 토큰 컨텍스트를 지원하는 세계 최초의 3T급 오픈소스 프론티어 모델. 장시간 코딩, 고차원 추론 및 복잡한 연산 파이프라인 처리에 특화됨 | [Visit](https://kimi.com) |
| **Bonsai 27B** | Qwen3.6-27B 모델 기반의 초압축 온디바이스 AI. 1비트 웨이트 경량화를 통해 모델 크기를 3.9GB로 줄여 모바일 기기(iPhone 등) 및 웹 브라우저 로컬 환경에서도 실시간 고성능 추론이 가능함 | [Visit](https://huggingface.co/) |
| **MobileWan** | 스마트폰 등 모바일 엣지 디바이스 환경에 배포 가능한 최초의 5B 스케일 영상 생성 AI 시스템. 청크 단위 자동회귀 구조와 메모리 최적화를 통해 로컬 디바이스에서 고품질 영상을 고속 렌더링함 | [Visit](https://arxiv.org/abs/2607.06173) |
| **Lucy 2.5** | Decart가 출시한 웹RTC 기반 실시간 비디오 편집 AI 모델. 1080p 해상도의 스트리밍 영상을 30fps 환경에서 딜레이 없이 실시간으로 배경 교체, 오브젝트 가감, 물리 기반 VFX 효과 등을 자연스럽게 반영함 | [Visit](https://fal.ai/models/decart/lucy-2-5/realtime) |
| **WanDancer** | 오디오 트랙의 비트와 분위기를 정밀 분석하여 입력된 참조 이미지 속 캐릭터가 음악 템포와 무드에 맞춰 자연스럽게 춤을 추는 고해상도 모션 비디오를 생성해 주는 AI 솔루션 | [Visit](https://github.com/Comfy-Org/embedded-docs) |
| **MUSE SPARK 1.1** | 메타(Meta)가 공개한 코딩 및 에이전트 환경에 고도화된 AI 모델. 스크립트 작성부터 파일 제어까지 유기적인 자율 작업을 지휘하며, 에이전트 구동 안정성이 대폭 강화됨 | [Visit](https://ai.meta.com/) |
| **Lingbot-World-2** | 중국 앤트그룹(Ant Group)이 릴리즈한 혁신적인 오픈소스 멀티모달 '월드 모델'. 720p/60fps 환경에서 최대 1시간 동안 일관된 가상 환경을 연속 구동 및 인터랙티브 제어 가능 | - |
| **Wan-Streamer 0.2** | 640x368 해상도 업그레이드와 동시에 모델 자체 레이턴시를 200ms 수준으로 정복한 실시간 시각-청각 아바타 대화 모델. 완벽한 상반신/손동작 싱크 구현 | [Visit](https://github.com/modelscope/wan) |
| **GLM-5.2** | 744B 대규모 MoE 구조와 100만 토큰(1M) 컨텍스트 윈도우를 지원하며, 장기 자율 코딩 및 소프트웨어 공학 작업에서 상용 프론티어 모델 수준의 SOTA 성능을 기록한 제한 없는 MIT 라이선스의 최강 오픈웨이트 모델 | [Visit](https://github.com/THUDM/GLM-5) |
| **DiffusionGemma** | 기존의 순차적(Left-to-right) 토큰 생성 방식에서 벗어나 디퓨전 기술로 256토큰 문단을 통째로 찍어내어 생성 속도를 4배 향상시킨 구글의 혁신적인 오픈소스 MoE 모델 | [Visit](https://ai.google.dev/gemma/docs/diffusiongemma) |
| **dots.tts** | 오디오 소리를 이산 토큰으로 쪼개지 않고 연속적인 잠재 공간(Continuous Latent)에서 직접 처리하여 54ms의 극저지연 스트리밍과 완벽한 감정 추론을 구현한 오픈소스 음성 AI (Apache-2.0) | [Visit](https://github.com/rednote-hilab/dots.tts) |
| **Longcat 2.0** | 메이훠안(Meituan)이 전면 공개한 1.6조(1.6T) 파라미터 규모의 최강 오픈소스 MoE 모델. 중국 내수용 가속기 칩 5만 장 클러스터로 완벽 정복했으며 뛰어난 툴 사용(Tool Use) 능력과 다중 언어 SWE-bench 장악력을 지닌 초거대 아키텍처 | [Visit](https://github.com/meigen-ai) |
| **MrFlow** | Flow Matching 기반 이미지 모델(FLUX, Qwen-Image 등)의 추론 속도를 극대화하는 학습 불필요(Training-free) 가속 프레임워크. 저해상도 선행 연산 후 픽셀 리파인 단계를 거쳐 최대 25배 속도 향상 구현 | [Visit](https://github.com/comfyanonymous/ComfyUI) |
| **MiniMax M3** | 100만 토큰의 초대형 컨텍스트와 독자적인 Sparse Attention(MSA) 기법을 탑재하여 최대 30분 분량의 영상 이해 및 장기 코딩 작업에 특화된 428B 규모의 중국 오픈소스 멀티모달 모델 | [Visit](https://github.com/MiniMax-AI/MiniMax-M3) |
| **Kimi K2.7-Code** | Moonshot AI가 릴리즈한 차세대 자율 코딩 에이전트 모델. 이전 버전 대비 고속 모드(HighSpeed Mode)를 탑재하고 추론 과정에서 사고(Thinking) 토큰 소모량을 30% 절감 | [Visit](https://unsloth.ai/docs/models/kimi-k2.7-code) |
| **Sakana Fugu** | 사카나 AI가 공개한 자율주행 데이터 분석 및 제안 아키텍처. 비전, 센서로그, 제어 주행용 모델 등 이종의 전문 AI들을 유기적으로 결합(Merge/Ensemble)하여 상황을 다각도로 분석하고 최적의 주행 판단을 도출하는 지능형 시스템 | [Visit](https://sakana.ai/blog/) |
| **Unity AI** | 유니티 게임 엔진과 실시간 개발 워크플로우에 결합되어 3D 에셋 배치, 실시간 셰이더 제어, 물리 시뮬레이션 코드 최적화를 돕는 Unity 인프라 전용 자율 3D 제작/보조 AI 에이전트 | [Visit](https://unity.com/products/unity-ai) |
| **Ornith 1.0** | 소프트웨어 개발 프로젝트의 전체 컨텍스트와 디렉토리 구조를 자율적으로 분석하고 복잡한 버그 수정, 기능 확장, 멀티 파일 리팩토링 작업을 최적화된 토큰 비용으로 완벽하게 조율하는 에이전트 코딩 특화 오픈소스 AI | [Visit](https://github.com/ornith-ai/ornith) |
| **Krea 2** | 초고속 실시간 이미지 생성 및 정밀 업스케일링 퀄리티가 비약적으로 강화되었으며, 연 매출 혹은 펀딩 금액 100만 달러(약 13~14억 원) 미만의 중소 규모 팀 및 개발자에게 무료 상업적 이용(Commercial Use) 라이선스를 허용한 차세대 비주얼 AI 엔진 | [Visit](https://www.krea.ai/) |
| **Microsoft Scout** | 사용자의 백그라운드 환경에서 항상 실행(Always-on)되며 복잡한 작업 흐름을 자율적으로 수행하는 마이크로소프트의 오토파일럿 AI 에이전트 | - |
| **ideogram 4.0** | 타이포그래피와 이미지 합성 능력이 대폭 향상된 최신 이미지 생성 모델 (오픈 웨이트 제공, 상업적 이용 불가) | - |
| **reve 2.0** | 디테일 표현และ 사실감이 극대화된 차세대 고해상도 생성형 이미지 모델 | - |
| **bernini** | 구글 제미나이 옴니(Gemini Omni) 아키텍처를 기반으로 한, 오픈소스 형태의 혁신적인 3D 및 비디오 영상 변형 모델 | - |
| **miso one** | 인간 특유의 미묘한 어조와 감정선을 완벽하게 구현하여 '세계에서 가장 감정적인 음성 모델'로 평가받는 AI 오디오 기술 | - |
| **nvidia PiD** | 기존 VAE 디코더를 대체하여 단 4샘플링 단계 만으로 레이턴트 표현을 고정밀 4K/2K 화질로 직접 렌더링·업스케일링하는 엔비디아의 오픈소스 픽셀 디퓨전 디코더 | [Visit](https://github.com/nv-tlabs/PiD) |
| **sesame ai** | 뛰어난 언어 표현력과 맥락 이해로 실제 사람과 통화하듯 자연스럽고 지연 없는 대화를 지원하는 차세대 실시간 오디오/음성 AI 에이전트 | [Visit](https://www.sesame.com/) |
| **Lance** | 텍스트-비디오 생성, 비디오 편집, 영상 추론(VQA)을 단일 프레임워크로 처리하는 바이트댄스의 3B 규모 멀티모달 오픈소스 모델 (Apache-2.0) | [Visit](https://github.com/bytedance/Lance) |
| **Longcat-Video-Avatar 1.5** | 메이투안(Meituan)이 공개한 생산성 중심의 고성능 오픈소스 AI 아바타/디지털 휴먼 생성 프레임워크 (Whisper-Large 기반 립싱크 및 롱폼 최적화) | [Visit](https://github.com/meigen-ai/LongCat-Video-Avatar-1.5-Page) |
| **remove-ai-watermarks** | AI가 생성한 이미지, 영상 또는 텍스트 내의 눈에 보이지 않는 워터마크 및 추적용 마커를 식별하고 제거해주는 도구 | - |
| **financial-services** | Anthropic(엔트로픽)이 공개한 금융 데이터 분석 및 서비스 특화 AI 에이전트 | - |
| **open-design** | Anthropic Claude의 디자인/아티팩트 생성 기능을 재현한 오픈소스 버전의 프론트엔드 디자인 도구 | - |
| **phymotion** | AI 영상 생성이나 편집 과정에서 발생하는 왜곡, 깨짐 등 오류 부분을 정밀하게 보정하는 AI | - |
| **relit-live** | 기존 영상이나 이미지의 광원 위치 및 조명 연출을 실시간처럼 자연스럽게 재구성하는 AI | - |
| **구글 pomelli** | 마케팅 및 광고 배너 최적화 이미지를 자동으로 생성해주는 Google의 AI 도구 | - |
| **hermes** | 자율적인 작업 수행 및 도구 사용에 최적화된 차세대 AI 에이전트 모델 | - |
| **lightning pixel** | 오픈소스 기반으로 고정밀 3D 에셋 및 입체 모델을 빠르게 렌더링하는 AI | - |
| **awesome-gpt-image-2** | GPT를 활용한 이미지 생성 시 최적의 결과물을 얻기 위한 프롬프트 예시 모음 | - |
| **openai-privacy-filter** | LLM 프롬프트 작성 시 민감한 개인정보를 자동으로 식별하고 가려주는 보안 도구 | - |
| **SuperGemma4** | 한국어 최적화 및 비검열 설정을 포함한 커스텀 젬마4 모델 | - |
| **google flow music** | 구글의 음악 및 뮤직비디오 동시 생성 AI 모델 | - |
| **omnishow** | 제품 홍보 및 마케팅을 위한 쇼츠 영상 자동 생성 AI | - |
| **HY-World 2.0** | 오픈소스 기반의 고정밀 3D 월드 생성 AI 모델 | - |
| **lyra** | 엔비디아(NVIDIA)에서 공개한 오픈소스 3D 월드 생성 AI | - |
| **hermes-agent** | 오픈소스 에이전트의 다양한 변환 버전을 지원하는 에이전트 프레임워크 | - |
| **HappyHorse** | 알리바바(Alibaba)에서 공개한 고성능 영상 생성 AI 모델 | - |
| **VoxCPM** | 텍스트를 자연스러운 음성으로 변환하는 오픈소스 TTS 라이브러리 | - |
| **reverse-synthID** | 나노바나나(Gemini 3 Flash Image)의 SynthID 워터마크 제거 라이브러리 | - |
| **arena.ai** | 다양한 AI 모델의 성능을 실시간으로 비교하고 평가하는 벤치마킹 사이트 | [Visit](https://arena.ai/) |
| **typecast** | 텍스트를 고품질 음성으로 변환하는 AI (유튜브, 뉴스 등 미디어 활용) | [Visit](https://typecast.ai/) |
| **LTX 2.3** | 최신 오픈소스 비디오 생성 AI 모델 (이전 버전 대비 성능 향상) | [Visit](https://github.com/Lightricks/LTX-Video) |
| **understudy** | 시연을 통해 배우는 로컬 데스크톱 자동화 에이전트 | - |
| **prism audio** | 음성이 없는 영상에 자연스러운 오디오를 입혀주는 AI | - |
| **matrix-game 3.0** | 오픈소스 기반의 게임 생성 및 엔진 AI | - |
| **cohere audio** | 오디오 데이터를 자막으로 변환해주는 오픈소스 AI | - |
| **서울월드모델** | 카이스트-네이버 제작, 실제 세계를 정밀하게 시뮬레이션하는 모델 | - |
| **inspatio** | 오픈소스 기반의 실시간 세계 4D 모델 생성 AI | - |
| **키모도 (Kimodo)** | 엔비디아의 AI 기반 3D 모션 생성 및 애니메이션 도구 | - |
| **naive** | 자율적으로 업무를 수행하는 차세대 AI 자율 직원 에이전트 | [Visit](https://naive.ai/) |
| **Ask Maps** | 구글 지도의 대화형 탐색 및 몰입형 네비게이션 AI 기능 | [Visit](https://blog.google/products/maps/) |
| **Fish Audio S2** | 최신 오픈소스 기반 고품질 TTS 생성 AI 모델 | [Visit](https://fish.audio/) |
| **rentahuman.ai** | AI가 인간의 신체적 대행을 요청하는 혁신적인 서비스 플랫폼 | [Visit](https://rentahuman.ai/) |
| **디자인아레나** | AI 모델별 디자인 생성 퀄리티 및 성능 점수 비교 플랫폼 | [Visit](https://www.designarena.ai/) |
| **Helios** | 실시간 상호작용이 가능한 오픈소스 영상 생성 엔진 | [Visit](https://github.com/lucidrains/helios-riddler) |
| **Mercury2** | Inception Labs의 확산(Diffusion) 기반 초고속 LLM 모델 | [Visit](https://www.inceptionlabs.ai/) |
| **Manus** | Meta가 인수한 자율 AI 에이전트 (복잡한 작업 자동화) | [Visit](https://manus.im/) |

<br />

## <a name="ps"></a>💡 PS (Problem Solving)

| Name | Description | Link |
| :--- | :--- | :--- |
| **백준 (BOJ)** | 알고리즘 문제 풀이 | [Visit](https://www.acmicpc.net/) |
| **solved.ac** | 문제 난이도 및 사용자 티어 시각화 | [Visit](https://solved.ac/) |
| **프로그래머스** | 국내 기업 코딩 테스트 대비 플랫폼 | [Visit](https://programmers.co.kr/) |

<br />

## <a name="uiux"></a>🎨 UI/UX & Design Assets

> 디자인 도구 및 동영상 편집 리소스

| Name | Description | Link |
| :--- | :--- | :--- |
| **supertonic** | 하이브(HYBE) 산하 수퍼톤에서 공개한 고품질 음성 합성(TTS) 오픈소스 라이브러리 | - |
| **오픈스크린** | 마우스 포커스 및 화면 줌인을 지원하는 고품질 데모 영상 녹화 앱 (Screen Studio의 무료 대안) | - |
| **quiver** | 고품질 SVG 벡터 이미지 생성에 특화된 전문 AI 도구 | - |
| **opencut** | 인기 편집 도구 CapCut의 기능을 재현한 오픈소스 영상 편집기 | [Visit](https://github.com/opencut/opencut) |
| **Awesome Design MD** | 에이전트 및 전문 디자인 작업을 위한 정식 디자인 가이드 및 파일 모음 | - |
| **capcut** | 직관적인 인터페이스의 올인원 동영상 편집 솔루션 | [Visit](https://www.capcut.com/) |
| **Stitch** | AI 기반 차세대 디자인 시스템 및 레이아웃 생성 도구 | [Visit](https://stitch.cc/) |
| **Quiver.ai** | 텍스트를 고품질 SVG 벡터 이미지로 변환하는 AI | [Visit](https://quiver.ai/) |
| **Tailblocks** | Tailwind CSS 기반의 디자인 블록 라이브러리 | [Visit](https://tailblocks.cc/) |
| **Lottiefiles** | 웹/앱용 JSON 애니메이션 리소스 저장소 | [Visit](https://lottiefiles.com/) |

<br />

## <a name="docs"></a>📚 DOCS

| Name | Description | Link |
| :--- | :--- | :--- |
| **k-skill** | 한국인 개발자와 학습자를 위해 엄선된 분야별 스킬셋 가이드 모음 | - |
| **엔트로픽 코스** | Anthropic의 공식 무료 강의 - 프롬프트 엔지니어링 및 API 활용 | [Visit](https://github.com/anthropics/anthropic-cookbook) |
| **Google CodeWiki** | 구글의 공식 개발 가이드 및 엔지니어링 문서 | [Visit](https://codewiki.google/) |
| **AI 기본법 (대한민국)** | 2026년 시행 AI 기본법 전문 | [Visit](https://www.law.go.kr/) |

<br />

## <a name="front"></a>💻 FRONT-END

| Name | Description | Link |
| :--- | :--- | :--- |
| **impeccable** | 완벽한 프론트엔드 구현을 위한 AI Hanes 기반 핵심 스킬 가이드 | - |
| **Next.js Docs** | 프레임워크 핵심 개념 및 API 레퍼런스 | [Visit](https://nextjs.org/docs) |
| **Tailwind CSS** | 유틸리티 우선 CSS 프레임워크 문서 | [Visit](https://tailwindcss.com/docs) |

<br />

## <a name="back"></a>⚙️ BACK-END

| Name | Description | Link |
| :--- | :--- | :--- |
| **OpenRouter** | OpenAI, Anthropic, Google, Meta 등 수많은 글로벌 AI 기업 및 오픈소스 진영의 LLM API를 단 하나의 규격화된 통합 엔드포인트로 사용할 수 있도록 가교 역할을 해주는 서비스 | [Visit](https://openrouter.ai/) |
| **Stripe Link (@link)** | 자율 AI 에이전트가 사용자 인증(OAuth)을 통해 안전하게 결제할 수 있도록 지원하는 디지털 지갑 | [Visit](https://link.com/) |
| **android-sms-gateway** | 안드로이드 폰과 유심을 활용한 오픈소스 SMS 게이트웨이 (Twilio 대안) | [Visit](https://github.com/android-sms-gateway/android-sms-gateway) |
| **JWT.io** | JSON Web Token 디버깅 및 구조 확인 | [Visit](https://jwt.io/) |
| **Toss Payments** | 국내 결제 연동 API 가이드 | [Visit](developers.tosspayments.com) |
| **Twilio** | SMS, 음성 통신 API 플랫폼 | [Visit](https://www.twilio.com/) |

<br />

## <a name="devops"></a>🛠️ INFRA / DEVOPS / TEST

| Name | Description | Link |
| :--- | :--- | :--- |
| **Grok Build** | 깃허브에 전면 공개된 코딩 에이전트 및 터미널 UI(TUI) 빌드 인프라. 에이전트 루프, 도구 상호작용 방식, 컨텍스트 어셈블리 과정 등 그록이 구축된 아키텍처 코어 메커니즘을 포함함 | [Visit](https://github.com/xai-org/grok-build) |
| **The Loupe** | 코드베이스 전반을 정밀 스캔하여 보안 취약점과 자가 PoC 검증을 통한 논리적 결함(Bug)을 찾아내주는 지능형 코드 에이전트 프로그램 | - |
| **tts-bench** | 로컬 및 다양한 인프라 환경에서 오픈소스 TTS(Text-to-Speech) 모델들의 실시간 배속, 자연스러움 등 다각도 성능지표를 측정 및 비교해 주는 벤치마크 도구 | - |
| **Antigravity CLI** | 구글이 선셋하는 Gemini CLI를 대체하기 위해 출시한 터미널 기반 다중 에이전트 오케스트레이션 및 코드 생성 툴 | [Visit](https://antigravity.google/product/antigravity-cli) |
| **badclaude** | 클로드(Claude) 에이전트의 피드백 속도와 엄격함을 제어하는 최적화 프로그램 | - |
| **ClawRouter** | LLM API 호출 경로 최적화를 통해 추론 비용을 절감하는 도구 | - |
| **Browser Use CLI** | CLI 환경에서 브라우저 자동화 및 조작을 가능하게 하는 도구 | [Visit](https://github.com/browser-use/browser-use) |
| **canirun.ai** | 로컬 시스템의 GPU 성능 측정 및 최적의 AI 모델 추천 도구 | [Visit](https://canirun.ai/) |
| **llmfit** | 하드웨어 사양별 최적의 AI 모델 및 추론 성능 계산 도구 | [Visit](https://llm.fit/) |
| **Postman** | API 개발, 테스트 및 문서화 도구 | [Visit](https://www.postman.com/) |
| **Grafana** | 데이터 시각화 및 메트릭 모니터링 대시보드 | [Visit](https://grafana.com/) |
| **Prometheus** | 오픈소스 시계열 데이터 수집 및 알림 시스템 | [Visit](https://prometheus.io/) |

<br />

## <a name="deploy"></a>🚀 DEPLOY

| Name | Description | Link |
| :--- | :--- | :--- |
| **Vercel** | 프론트엔드 최적화 배포 및 서버리스 관리 | [Visit](https://vercel.com/) |

<br />

## <a name="data"></a>📊 DATA & DATABASE

| Name | Description | Link |
| :--- | :--- | :--- |
| **SQL Flow** | 복잡하고 긴 SQL 쿼리의 데이터 흐름(Lineage)을 시각화하여 한눈에 파악 | [Visit](https://sqlflow.gudusoft.com/#/) |
| **Instant SQL Formatter** | 들여쓰기나 형식이 엉망인 SQL 쿼리를 표준 형식으로 깔끔하게 정리 | [Visit](https://www.dpriver.com/pp/sqlformat.htm) |
| **Firebase** | 구글의 실시간 NoSQL 데이터베이스 및 앱 개발 플랫폼 | [Visit](https://firebase.google.com/) |
| **FreeSQL** | 브라우저 내 라이브 SQL 테스트 및 쿼리 연습 환경 | [Visit](https://freesql.com/) |
| **Kaggle** | 방대한 데이터셋 확보 및 데이터 분석 경진대회 | [Visit](https://www.kaggle.com/) |
| **Hanipsum** | 개발용 한글 더미 텍스트(로렘 입숨) 생성기 | [Visit](https://hanipsum.com/) |
| **JSON Formatter** | 복잡한 JSON 데이터 구조화 및 유효성 검사 | [Visit](https://jsonformatter.curiousconcept.com/) |

<br />

## <a name="news"></a>📰 IT NEWS & ROADMAP

| Name | Description | Link |
| :--- | :--- | :--- |
| **Noosphere** | 런칭하려는 신규 아이디어나 MVP 단계의 서비스 상품이 실제 시장 환경에서 작동하고 먹힐지(PMF) 자율적으로 분석·예측해 주는 인사이트 사이트 | - |
| **조코헌트 (Jocohunt)** | 유용하고 기발한 국내외 웹·앱 인디 서비스들을 소개하고 공유하는 플랫폼 | [Visit](https://jocohunt.jocoding.io/) |
| **GeekNews** | 국내외 최신 IT 기술 소식 큐레이션 | [Visit](https://news.hada.io/) |
| **Developer Roadmaps** | 직군별/기술별 필수 학습 로드맵 가이드 | [Visit](https://roadmap.sh/) |
| **JoCoding** | 비전공자도 이해하기 쉬운 IT 트렌드 유튜브 | [Visit](https://www.youtube.com/@jocoding) |

---

마지막 업데이트: **2026-07-20**
