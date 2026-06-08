# 05. 오디오 생성 로그

## 1. 사용 목적

VERI AUTONOMY 광고 영상에 AI로 생성한 청각 요소를 포함한다. 청각 요소는 배경음악, 내레이션, 효과음 중 1개 이상이면 충족되지만, 본 프로젝트에서는 가능하면 **배경음악 + 짧은 내레이션 + 전환 효과음**을 함께 사용한다.

## 2. 사용 도구 계획

| 구분 | 도구 | 사용 목적 | 상태 |
|---|---|---|---|
| 배경음악 | Suno 또는 Canva Audio | 42초 광고용 배경음악 생성 | 사용 예정 |
| 내레이션 | CapCut AI 음성 또는 ElevenLabs | 짧은 한국어/영어 내레이션 생성 | 사용 예정 |
| 효과음 | CapCut/Canva AI 효과음 | 전환음, 브랜드 리빌, 연결 효과 | 필요 시 사용 |

## 3. 오디오 콘셉트

| 항목 | 내용 |
|---|---|
| 분위기 | 정제된 기술 브랜드 광고, 신뢰감, 미래적이지만 과하지 않음 |
| 템포 | 중간 속도, 차분한 진행감 |
| 악기/질감 | 소프트 신스, 낮은 패드, 가벼운 디지털 펄스 |
| 감정선 | 복잡성 → 안내 → 신뢰 → 브랜드 각인 |
| 금지 | 특정 상업 음악 모방, 특정 가수/성우 목소리 모사, 과도하게 공격적인 음악 |

## 4. 배경음악 생성 프롬프트

```text
A clean premium technology brand advertisement background music track, 42 seconds, soft synth pad, subtle digital pulse, calm and trustworthy mood, futuristic but not aggressive, suitable for AI autonomy and research brand commercial, no vocals.
```

예상 파일명:

```text
outputs/veri_autonomy_bgm_42s.wav
```

## 5. 내레이션 스크립트

| 구간 | 내레이션 |
|---|---|
| 씬 1 | AI와 자율시스템의 세계는 빠르게 복잡해지고 있습니다. |
| 씬 2 | 흩어진 정보 속에서, 방향을 잡아주는 안내자가 필요합니다. |
| 씬 3 | VERI AUTONOMY. Verified Autonomy, Made Visible. |
| 씬 4 | Trusted AI. Safe Autonomy. Research Frontier. Insight Intelligence. |
| 씬 5 | 검증 가능한 구조로, 더 명확하게. |
| 씬 6 | VERI AUTONOMY. Visit veriautonomy.com. |

## 6. 내레이션 생성 프롬프트

```text
차분하고 신뢰감 있는 기술 브랜드 광고 내레이션. 과장하지 말고 또렷하게 읽어 주세요. 연구, 안전, 자율시스템, 인사이트를 다루는 프리미엄 테크 브랜드 느낌으로 약 35~42초 길이에 맞춥니다.
```

예상 파일명:

```text
outputs/veri_autonomy_narration_42s.wav
```

## 7. 효과음 계획

| 효과음 | 사용 구간 | 목적 |
|---|---|---|
| Soft data pulse | 씬 1 | 정보 흐름 등장 |
| Guide appear | 씬 2 | 프루피 등장 |
| Brand reveal chime | 씬 3 | 브랜드 등장 |
| Connection pulse | 씬 4 | 핵심 가치 연결 |
| Resolve tone | 씬 5 | 정보 구조화 |
| Closing chime | 씬 6 | CTA 마무리 |

## 8. 생성 후 기록할 항목

```text
- 사용 도구:
- 생성 날짜:
- 프롬프트:
- 출력 파일명:
- 길이:
- 결과 요약:
- 문제점:
- 수정 여부:
```

## 9. 저작권/윤리 확인

- 기존 상업 음악을 직접 모방하지 않는다.
- 특정 가수, 성우, 유명인의 목소리를 모사하지 않는다.
- 생성 도구의 이용 조건을 확인하고 제출문서에 도구명을 기록한다.
- 오디오 파일에 개인정보, 계정정보, API Key, 토큰이 포함되지 않도록 한다.
