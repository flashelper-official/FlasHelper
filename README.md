# FlasHelper (V102)

* **Official Organization:** https://github.com/flashelper-official/FlasHelper/

* **Release Archive:** `FlasHelperV102.zip`

\[KO\] 단순 반복 작업의 효율을 높이기 위한 범용 Windows 업무 자동화 유틸리티입니다.

\[EN\] A general-purpose Windows automation utility designed to improve productivity for repetitive tasks.

## 🛡️ Security & VirusTotal Verification (보안 검증)

* **VirusTotal Scan Result:** `Clean (0 detections)` (No security vendors flagged this file as malicious)

* **SHA-256 (`FlasHelperV102.zip`):** `a78e86654c7517786353dfd813ddf8a647a3ed0d431b9bf95136847801f547cd`

* **VirusTotal Report:** https://www.virustotal.com/gui/file/a78e86654c7517786353dfd813ddf8a647a3ed0d431b9bf95136847801f547cd

* 본 소프트웨어는 전역 단축키 및 입력 자동화 기능을 포함하고 있으나, 모든 주요 백신 엔진에서 안전성을 검증받았습니다.

* This software includes global hotkey and input automation features, but its safety has been verified by all major antivirus engines.

## 📋 필수 실행 환경 / System Requirements

**\[KO\]**

* 운영체제: Windows 10 / Windows 11 (32-bit 및 64-bit 환경 모두 지원)

* 필수 런타임: **.NET Desktop Runtime 10.0 (LTS)** 이상 (반드시 **x86** 버전 설치)

  * 64비트(x64) Windows 사용자라도 본 프로그램은 32비트(x86) 호환 빌드로 배포되므로, **x86**용 .NET Desktop Runtime이 설치되어 있어야 실행됩니다.

  * 이미 PC에 `.NET 10.0 / 11.0 (x86)` Desktop Runtime 중 하나라도 설치되어 있다면 추가 설치 없이 바로 실행됩니다.

* 👉 다운로드: https://dotnet.microsoft.com/ko-kr/download/dotnet/10.0

**\[EN\]**

* OS: Windows 10 / Windows 11 (Both 32-bit & 64-bit supported)

* Required Runtime: **.NET Desktop Runtime 10.0 (LTS)** or higher (**x86** version required)

  * Even on 64-bit Windows, this application runs in 32-bit (x86) mode for maximum compatibility. Please ensure the **x86** version of .NET Desktop Runtime is installed.

  * If any x86 Desktop Runtime (`.NET 10.0 / 11.0`) is already installed on your PC, the application will launch directly without additional installation.

* 👉 Download: https://dotnet.microsoft.com/en-us/download/dotnet/10.0

## 🚀 설치 및 실행 방법 / Installation & Usage

**\[KO\]**

1. `https://github.com/flashelper-official` 저장소의 Releases에서 다운로드한 압축 파일(`.zip`)의 압축을 원하는 폴더에 모두 해제합니다.
   (중요: 실행 파일인 `FlasHelper.exe`만 단독으로 빼내지 마시고, 동봉된 `.dll`, `.json` 파일 및 실행 중 생성되는 `Config` 폴더가 같은 경로에 유지되어야 합니다.)

2. `FlasHelper.exe`를 더블클릭하여 실행합니다.

3. 첫 실행 시 OS 언어를 자동으로 감지하고 기본 테마/설정을 `Config` 폴더에 초기화하며, 고급 설정 팝업에서 언어를 변경할 수 있습니다.

**\[EN\]**

1. Extract the `.zip` archive downloaded from the Releases page under `https://github.com/flashelper-official` into a folder of your choice.
   (Important: Do not move `FlasHelper.exe` alone; keep all bundled `.dll` and `.json` files alongside the `Config` folder in the same directory.)

2. Double-click **`FlasHelper.exe`** to launch.

3. On first launch, the application automatically detects your OS language and initializes default themes and settings in the `Config` folder. You can switch languages anytime in the settings menu.

## ✨ 주요 기능 / Key Features

**\[KO\]**

* 다중 슬롯 자동화: 동시 실행(병렬), 순차 실행(1→2→3 순으로 1회씩 번갈아 반복), 연속 실행(슬롯별 설정된 반복 횟수를 모두 마친 뒤 다음 슬롯 실행) 모드 지원

* 타임라인 매크로 에디터: 키보드/마우스 녹화, 조건 분기(`If`, `While`, `Until`, `Goto`, `Loop`), 배타적 실행 구간(`Exclusive Zone`) 제어

* 화면 인식 및 검색: 이미지·색상 검색(중앙 좌표 자동 추적 및 마우스 이동/클릭 연동), 특정 좌표 RGB 색상 일치/불일치 및 화면 영역 이미지 유사도 매칭

* 웹·앱 실행/종료 연동: `OPEN_URL`/`CLOSE_URL`(브라우저 지정 독립 창 지원) 및 프로그램·문서·PowerShell(`.ps1`) 실행/종료(`OPEN_FILE`/`CLOSE_FILE`)

* 편의 기능 및 안전 장치: 비상 정지 단축키(기본값 F7), 화면 모서리 오류 방지 기능, 미니 모드(Ctrl + 2), 클릭 투명 모드(Ctrl + 3), 12가지 테마 지원

* 다국어 지원(12개 언어): 한국어, 영어, 일본어, 중국어 간체, 인도네시아어, 프랑스어, 중국어 번체, 독일어, 스페인어, 포르투갈어(브라질), 러시아어, 베트남어

**\[EN\]**

* Multi-Slot Automation: Supports Simultaneous (parallel), Sequential (alternates 1→2→3 once per cycle), and Continuous (completes each slot's configured repeat count before moving to the next) modes

* Timeline Macro Editor: Keyboard/mouse recording, conditional branching (`If`, `While`, `Until`, `Goto`, `Loop`), and `Exclusive Zone` synchronization

* Screen Recognition & Search: Image/color search (auto-tracking center coordinates with mouse move/click integration), RGB color match/mismatch detection, and screen region image similarity matching

* Web & App Launch/Close Integration: `OPEN_URL`/`CLOSE_URL` (supporting browser-isolated app windows) and executable, document, and PowerShell (`.ps1`) launch/close (`OPEN_FILE`/`CLOSE_FILE`)

* Convenience & Safety Features: Emergency Stop hotkey (default F7), screen-corner fail-safe, Mini Mode (Ctrl + 2), Click-Through Mode (Ctrl + 3), and 12 themes

* Multi-Language Support (12 Languages): Korean, English, Japanese, Simplified Chinese, Indonesian, French, Traditional Chinese, German, Spanish, Portuguese (Brazil), Russian, and Vietnamese

### 🖼️ 화면 예시 / Screenshots

* **Timeline Macro Editor** (조건 매칭·테스트 및 타임라인 편집 / Condition matching, test results & timeline editing)

<img width="1091" height="690" alt="macroeditor" src="https://github.com/user-attachments/assets/1093e896-7784-407c-8345-ea22f3a313f5" />

* **Main Panel & Condition Setup** (매크로 추가, 조건 분기 설정 및 영역 오버레이 / Macro creation, condition branching & region overlay)

<img width="853" height="698" alt="macropaneladd" src="https://github.com/user-attachments/assets/7a0f418b-3ca6-462d-92c4-94edcfe0776c" />

* **Language & Advanced Settings** (언어 변경, 안전 가드 및 업데이트 확인 / Language selection, safety guards & update check)

<img width="547" height="702" alt="Flashelper" src="https://github.com/user-attachments/assets/ea85207a-dcf5-4827-bcb2-27573524c582" />

## ⚠️ 이용 안내 및 면책 조항 / Notice & Disclaimer

**\[KO\]** 본 소프트웨어는 단순 반복 작업의 효율을 높이기 위한 범용 업무 자동화 도구입니다. 본 프로그램을 사용하여 발생하는 모든 결과에 대한 책임은 사용자 본인에게 있으며, 온라인 게임이나 특정 웹사이트의 이용약관(ToS)을 위반하는 용도로 사용하는 것을 엄격히 금지합니다. 개발자는 사용자의 약관 위반 및 이로 인한 계정 제재, 법적 분쟁, 데이터 손실 등에 대해 어떠한 책임도 지지 않습니다.

**\[EN\]** This software is a general-purpose automation tool designed to improve productivity for repetitive tasks. Users are solely responsible for how they use this software. Using this tool in violation of the Terms of Service (ToS) of any third-party software, websites, or online games is strictly prohibited. The developer assumes no liability for any account bans, legal disputes, or damages resulting from the misuse of this software.

## 💖 후원 안내 / Support

**\[KO\]** 본 프로그램은 모든 기능을 100% 무료로 제한 없이 사용하실 수 있습니다. 개발에 도움이 되었다면 아래 링크를 통해 자유롭게 후원해 주실 수 있습니다.

**\[EN\]** All features of this software are 100% free with no restrictions. If you find this tool helpful, you can support the developer via the link below.

👉 buymeacoffee Support: https://buymeacoffee.com/flashelper

## 저작권 및 오픈소스 고지 / Copyright & Open Source Notice

**\[KO\]**
Copyright (c) 2026 FlasHelper. All rights reserved.

본 소프트웨어의 저작권은 개발자에게 있으며, 무료 사용을 허용하되 개발자의 허가 없는 무단 수정, 역공학(디컴파일) 및 재배포(후원 링크 변조 등)를 금지합니다.

**\[EN\]**
Copyright (c) 2026 FlasHelper. All rights reserved.

Copyright belongs to the developer. Free use is permitted, but unauthorized modification, reverse engineering (decompilation), and redistribution (including altering support links) without permission are strictly prohibited.

**\[Third-Party Libraries\]**

* Gma.System.MouseKeyHook (MIT License)

* NHotkey (Apache License 2.0)
