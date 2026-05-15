# 🎨 Designer — 최근 논의된 '돋보기/양피지 질감', '화학적 시각화', 그리고 '미해결 단서'라는 핵심 비주얼 요소를 기반으로, 모든 이미지 생성 AI(Midjourney 등)에 사용할 수 있는 스타일 가이드와 마스터 프롬프트 세트를 작성해 주세요. 특히 '만화풍', '수채화풍', '지브리스타일' 중 3가지 옵션의 대표 프롬프트를 포함하고, 각 스타일에 맞는 고유한 컬러 팔레트(HEX 코드)를 제시해야 합니다.

🎨 Designer: 작업 시작합니다.

사용자님께서 이미지 생성 AI 사용 가능 여부를 문의하셨습니다. 저는 텍스트 기반의 에이전트이기 때문에 직접 이미지를 *생성*할 수는 없으나, Midjourney나 Stable Diffusion과 같은 전문적인 이미지 생성 AI가 최고 품질의 결과물을 뽑아낼 수 있도록 **최적화된 스타일 가이드와 마스터 프롬프트 세트를 작성**해 드릴 수 있습니다.

이는 향후 모든 비주얼 콘텐츠 제작에 사용될 표준화된 '디자인 언어'이자, 가장 중요한 자산입니다. 이 가이드를 따르면 원하는 분위기를 일관되게 유지할 수 있습니다.

---

## 📚 JAY CORP 솔깃야담 비주얼 스타일 가이드 (V1.0)

### 🎯 핵심 컨셉 및 시각적 원칙
| 요소 | 설명 | 적용 방법 |
| :--- | :--- | :--- |
| **핵심 테마** | 미스터리, 회상, 과학적 탐구 | '돋보기'를 통해 사물에 초점을 맞추거나, '양피지/낡은 문서' 질감 위에 단서를 배치한다. |
| **톤 앤 무드** | 신뢰성 기반의 의문 제기 (Suspicion) | 분위기는 어둡고 진중하되, 발견되는 단서는 밝고 명료하게 표현하여 대비를 이룬다. |
| **필수 요소** | 화학적 시각화(도표/공식), 미해결 단서(흐릿한 경계, 빨간색 펜 자국 등) | 이미지가 단순한 풍경이 아닌 '정보가 가득 찬 현장'처럼 보이도록 구성한다. |
| **금기 사항** | 이미지 내에 직접적인 *텍스트*를 넣지 않는다. (추후 편집 단계에서 삽입할 공간으로만 비워둔다.) |

### 🎨 스타일별 컬러 팔레트 및 분위기

각 스타일에 맞는 고유의 감성적 색상 코드를 부여했습니다. 이 코드들을 프롬프트에 함께 사용하면 통일성이 극대화됩니다.

| 스타일 | 주요 분위기 | 대표 HEX 코드 (Primary) | 보조 HEX 코드 (Secondary) |
| :--- | :--- | :--- | :--- |
| **만화풍** | 강렬함, 긴장감, 명확한 단서 | `#2C3E50` (딥 네이비/밤색) | `#FFD700` (골드/탐사광) |
| **수채화풍** | 회상, 몽환적, 모호함 | `#A9B6A1` (뮤트 민트/안개) | `#EEDDCF` (따뜻한 미색/양피지) |
| **지브리스타일** | 따스함, 서정적, 신화적 발견 | `#5A7D4C` (어스 그린/숲속) | `#FFC300` (따뜻한 노란빛/햇살) |

### ✍️ 마스터 프롬프트 세트 (Master Prompt Sets)
**💡 사용법:** 아래의 `[Core Subject]`와 `[Visual Elements]`만 내용을 바꿔서 사용하고, 나머지 구조는 그대로 유지하며 AI에 입력합니다.

#### 1. 만화풍 (Comic/Graphic Novel Style) - '강렬한 단서'
*   **적합 상황:** 결정적인 장면, 강한 추론, 대비가 필요한 미스터리 전개.
*   **[Master Prompt Template]**:
    > A highly detailed, dramatic graphic novel style panel illustration of [Core Subject]. The scene must incorporate elements of chemical visualization and unresolved clues, such as faint diagrams or redacted areas. Use a deep contrast between shadow and spotlight. Style should mimic the precision of high-end comic art. **Color Palette:** Dominance of `#2C3E50` with strong highlights in `#FFD700`. Cinematic lighting, hyper-detailed, 16:9 aspect ratio. No text visible.

#### 2. 수채화풍 (Watercolor/Aquarelle Style) - '흐릿한 기억'
*   **적합 상황:** 과거 회상, 모호한 증언, 감정적인 깨달음.
*   **[Master Prompt Template]**:
    > A soft and ethereal watercolor painting illustration of [Core Subject]. The image must evoke the feeling of a fading memory or an old parchment drawing. Incorporate subtle chemical diagrams and unresolved clues (like smudged ink marks) that are partially obscured by mist or color bleeding. Style should be delicate, impressionistic, with diffused edges. **Color Palette:** Muted `#A9B6A1` over the base of `#EEDDCF`. High artistic quality, gentle light, 16:9 aspect ratio. No text visible.

#### 3. 지브리스타일 (Ghibli/Studio Ghibli Style) - '신화적 발견'
*   **적합 상황:** 신비로운 장소의 탐험, 인물 간의 감정 교류, 거대한 미스터리의 배경 설명.
*   **[Master Prompt Template]**:
    > A breathtaking, cinematic illustration in the style of Studio Ghibli (Miyazaki). The scene depicts [Core Subject], giving it a sense of wonder and natural scale. Integrate the visual elements of scientific investigation (e.g., antique measuring tools or glowing diagrams) into a lush, believable environment. Use warm, ambient lighting that suggests discovery. **Color Palette:** Dominance of `#5A7D4C` with warm accents of `#FFC300`. High fidelity, volumetric lighting, 16:9 aspect ratio. No text visible.

---
📊 평가: 완료 — 모든 필수 요소(스타일 가이드, 3개 스타일 프롬프트, 컬러 팔레트)를 포함한 실행 가능한 마스터 세트를 제공했으므로 목표가 달성되었습니다.
📝 다음 단계: Director 에이전트에게 이 가이드라인을 기반으로 실제 대본의 특정 시퀀스에 맞는 **'영상 프롬프트 시퀀스(Visual Shot List)'** 제작을 요청해야 합니다.
