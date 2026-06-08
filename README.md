# B1-2 VERI AUTONOMY AI Advertisement Submission

## 1. 프로젝트 개요

이 저장소는 코디세이 AI 네이티브 과정의 **B1-2 미션: AI로 글·그림·영상 만들어 나만의 광고 만들기** 제출용 저장소입니다.

본 프로젝트는 가상의/브랜드형 AI 기술 브랜드 **VERI AUTONOMY**를 대상으로, 생성형 AI를 활용한 43.30초 광고 영상을 제작했습니다.

## 2. 브랜드 정보

| 항목 | 내용 |
|---|---|
| 브랜드명 | VERI AUTONOMY |
| 광고명 | Verified Autonomy, Made Visible |
| 핵심 메시지 | Verified Intelligence for Safer Autonomy |
| 광고 목적 | 브랜드 인지도 강화 및 홈페이지/서비스 관심 유도 |
| 타겟 | AI, 로보틱스, 자율시스템, 기술 검증, 자동화 시스템에 관심 있는 사용자 |
| 톤앤매너 | 블랙/화이트/시안 블루 기반의 신뢰감 있는 프리미엄 테크 무드 |

## 3. 최종 제출 영상

| 항목 | 내용 |
|---|---|
| 최종 영상 파일 | `outputs/VERI_AUTONOMY_B1-2_final_ad_v1.mp4` |
| 영상 길이 | 43.30초 |
| 해상도 | 1920 x 1080 |
| 프레임레이트 | 30fps |
| 영상 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 최종 메시지 | Verified Intelligence for Safer Autonomy |

## 4. 제작 흐름

1. ChatGPT를 활용해 브랜드 콘셉트, 광고 메시지, 씬 구성, 카피를 기획했습니다.
2. AI 이미지 생성 도구를 활용해 광고용 키비주얼과 브랜드 캐릭터 프루피 장면을 제작했습니다.
3. 이미지 기반 영상 생성/변환 AI를 활용해 주요 장면을 짧은 모션 영상으로 변환했습니다.
4. Suno를 활용해 광고용 BGM을 생성했습니다.
5. CapCut에서 컷 편집, 자막, 로고, 장면 길이를 조정했습니다.
6. ffmpeg를 활용해 무음 영상과 최종 BGM을 결합하여 제출용 MP4를 완성했습니다.

## 5. 최종 씬 구성

| 순서 | 역할 | 화면 카피 |
|---:|---|---|
| 01 | 검증되지 않은 데이터 혼란 / 문제 제시 | Unverified data is everywhere. |
| 02 | 프루피가 데이터를 검증하는 장면 | Every signal is checked. |
| 03 | 검증 완료 전환 | - |
| 04 | 검증된 데이터 구조화 | From noise to verified structure. |
| 05 | 통제실/운영 레이어 진입 | Verified intelligence enters the control layer. |
| 06 | 검증된 데이터가 AI 시스템으로 구현되는 장면 | From verified data to working AI systems. |
| 07 | 브랜드 엔딩 | VERI AUTONOMY / Verified Intelligence for Safer Autonomy |

## 6. B1-2 미션 요구사항 대응

| 요구사항 | 대응 |
|---|---|
| 30초 이상 60초 이내 광고 영상 | 최종 43.30초 MP4로 충족 |
| 브랜드/캠페인 정의 | VERI AUTONOMY 브랜드 광고로 정의 |
| 이미지 생성 AI 사용 | 씬별 키비주얼 및 프루피 장면 제작에 사용 |
| 비디오 생성/변환 AI 사용 | 이미지 기반 모션 영상 제작에 사용 |
| 오디오 생성 AI 사용 | Suno 기반 BGM 제작 |
| 최종 편집 | CapCut에서 컷 편집, 자막, 로고, 길이 조정 |
| 마지막 브랜드 인지 장치 | 엔딩에 VERI AUTONOMY, 슬로건, 로고 삽입 |
| 프롬프트 수정 전/후 기록 | 프루피 등장/검증 장면 및 BGM 방향 수정 과정을 문서에 기록 |
| 개인정보/API Key 비노출 | README와 산출물에 민감정보 미포함 |

## 7. 포함 문서

| 파일 | 내용 |
|---|---|
| `01-brand-campaign-definition.md` | 브랜드/캠페인 정의 |
| `02-storyboard.md` | 씬별 스토리보드 |
| `03-image-generation-log.md` | 이미지 생성 과정 |
| `04-video-generation-log.md` | 비디오 생성/변환 과정 |
| `05-audio-generation-log.md` | 오디오 생성 과정 |
| `06-prompt-iteration-log.md` | 프롬프트 수정 전/후 기록 |
| `07-final-video-spec-and-checklist.md` | 최종 영상 사양 및 체크리스트 |

## 8. 공개 범위 안내

캐릭터 원본 이미지, 로고 원본, 3D 원본 파일, 중간 생성물 전체는 재사용 및 지식재산권 보호를 위해 공개 제출 저장소에는 포함하지 않았습니다.

본 저장소에는 평가에 필요한 최종 영상과 제작 설명 문서만 포함했습니다.

## 9. 최종 체크리스트

- [x] 브랜드/캠페인 정의
- [x] 스토리보드 작성
- [x] 이미지 생성 AI 사용
- [x] 비디오 생성/변환 AI 사용
- [x] 오디오 생성 AI 사용
- [x] 최종 광고 영상 30~60초 범위 충족
- [x] 마지막 장면에 브랜드명/슬로건/로고 포함
- [x] 개인정보/API Key 미포함
- [x] 최종 MP4 제출 가능 상태
