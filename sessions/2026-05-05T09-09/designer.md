# 🎨 Designer — Writer가 완성할 B단계의 세그먼트 아웃라인 구조를 받아, 90분 분량의 콘텐츠 전체에 적용될 '영상 프롬프트 시퀀스'의 가이드라인을 구축하세요. 특히 학술적 내용이 강조되는 부분(데이터 인터페이스, 고문서 이미지 등)과 극적인 전환점마다 필요한 비주얼 효과(글리치 트랜지션, 균열 효과 등)를 포함하여, 일관성 있는 톤앤매너의 전체 프롬프트 템플릿을 제작해 주세요. (이미지/영상 스타일은 '만화 풍 또는 수채화풍' 중 하나로 통일하여 제안합니다.)

🎨 Designer: 작업 시작합니다.

## 🌊 영상 프롬프트 시퀀스 가이드라인 구축 및 적용
**(B-Stage 본론 아웃라인 기반, 90분 분량 콘텐츠용)**

### 1. 핵심 아트 디렉션 결정 (Style & Tone)

*   **선택 스타일:** **수채화풍 (Watercolor Style)**
    *   **선정 이유:** 수채화는 '시간이 흐른 흔적', '잊혀진 기억', '희미한 기록'이라는 감성적인 무게감을 가장 잘 전달합니다. 이는 시니어 타겟의 'Nostalgia(회상)'와 콘텐츠가 가진 '학술적 미스터리'라는 두 축을 결합하는 데 최적입니다.
    *   **톤앤매너:** Vintage, Academic, Suspenseful (빈티지, 학술적, 긴장감)
    *   **핵심 시각 효과:** Paper texture overlay (종이 질감), Faded edges (바랜 가장자리), Ink bleeding effect (잉크 번짐 효과).

### 2. 마스터 프롬프트 템플릿 (Master Prompt Template)

모든 이미지/영상 클립은 아래 구조를 따르며, AI 명령어는 **Midjourney v6.0** 기준을 목표로 합니다.

| 요소 | 역할 | 필수 포함 내용 및 지침 |
| :---: | :--- | :--- |
| **[A] 묘사 (Subject)** | 영상의 핵심 시각 자료 (무엇이 보이는가) | 구체적이고 명확하게 정의. 예: 고대 항해사가 펼치는 양피지 지도, 지자기 변화를 나타내는 복잡한 그래프 등. |
| **[B] 학술 장치 (Academic Props)** | 전문성/신뢰도 부여 요소 | 돋보기(Magnifying Glass), 필사본 조각(Manuscript fragments), 데이터 인터페이스 오버레이(Data Overlay UI), 연필 스케치, 과학 기구(Astrolabe). **이미지에 반드시 포함되어야 함.** |
| **[C] 스타일 및 분위기 (Style & Mood)** | 전반적인 룩앤필 통일성 유지 | `watercolor painting style, hyper detailed, soft focus, faded sepia tone, vintage archival quality, cinematic lighting` 등 필수 키워드 조합. |
| **[D] 기술적 제약 (Constraints)** | AI 출력의 품질 및 규칙 강제 | `No text in the image`, `high resolution 8k`, `shot on film grain`, `--ar 16:9` 등의 명령어 추가. |

**▶ 최종 구조 공식:**
> [A] + [B] + [C] + [D]

### 3. 비주얼 시스템 가이드라인 (Visual System Guideline)

#### A. 필수 시각 요소 및 구현 원칙
1. **텍스트 처리:** 이미지 자체에 설명이나 문구는 절대 들어가지 않습니다. 모든 텍스트 정보(날짜, 좌표 등)는 *후반 작업에서 UI 오버레이*로 처리합니다.
2. **균열/오류 효과 (Glitch/Crack):** 학술적 긴장감이 고조되는 순간 (예: 의문 제기 직전), 영상 프롬프트에 `subtle crack effect, data glitch overlay on the edges`를 추가하여 시각적 불안정함을 극대화합니다.
3. **앵글 활용:** 단순한 풀샷(Wide Shot)보다는, 특정 단서나 데이터에 집중하는 클로즈업(Close-up)이나 돋보기 뷰(Magnifying Glass View)를 적극적으로 사용해야 합니다.

#### B. 컬러 팔레트 (HEX Code)
*   **메인:** `#2D3E50` (깊은 인디고/남색 - 신뢰, 미스터리)
*   **액센트 1:** `#B87333` (황갈색 브라운 - 고대 양피지, 시간의 흐름)
*   **액센트 2:** `#A0522D` (짙은 갈색/카카오톤 - 지도의 잉크, 진실 추적)

### 4. 세그먼트별 프롬프트 시퀀스 초안 (Actionable Output)

Writer의 아웃라인에 따라 가장 효과적인 비주얼 콘셉트를 매칭하여 구체적인 프롬프트를 제공합니다.

#### I. ACT 1: 논쟁점 제시 및 의문 제기 (S-01 ~ S-03)
**🎨 목표:** 학술적 무게감을 통해 '정상'의 틀을 보여준 후, '오류'를 발견하며 긴장감 조성.

| Scene | 내용/핵심 시각 자료 | 프롬프트 타입 및 핵심 키워드 | 예시 Midjourney Prompt (수채화풍) |
| :---: | :--- | :--- | :--- |
| **S-01** | 피리 레이스 지도의 객관적 분석 (전체 맵) | **[Wide Shot/Archival]** 전면 펼쳐진 고대 양피지 지도, 수많은 항로와 좌표가 묘사됨. 주변에 돋보기가 놓여있음. | `Watercolor painting of an ancient, vast parchment map, depicting complex maritime routes and coordinates. A magnifying glass is resting on the center. Subtle ink bleeding effect. Hyper-detailed, faded sepia tone, academic archival quality --ar 16:9` |
| **S-02** | '이상 좌표'의 발견 및 의문 제기 (특정 점) | **[Extreme Close-up/Focus]** 지도 위의 특정 미지의 지점(좌표)을 돋보기로 확대하는 순간. 주변은 흐릿하고, 이 지점만 강한 빛으로 강조됨. | `Macro watercolor shot focusing on a specific set of mysterious coordinates marked on an old parchment map. The area is highlighted with a faint, glowing blue energy (non-text). Intense suspicion and discovery mood. Hyper detailed --ar 16:9` |
| **S-03** | 전설과 학술의 접점 (잃어버린 문명) | **[Conceptual/Fantasy]** 지도를 배경으로 아틀란티스나 레무리아 같은 거대한, 신비로운 고대 도시의 실루엣이 수채화처럼 떠오르는 모습. | `Watercolor painting of a submerged, mythical ancient civilization silhouette (Atlantis style), appearing to float above the visible surface map. The style must be ethereal and melancholic. Soft focus, deep indigo color palette --ar 16:9` |

#### II. ACT 2: 전문 탐구 및 논쟁 심화 (S-04 ~ S-05)
**🎨 목표:** 추상적인 과학 개념을 시각적 데이터와 고대 기록으로 구현하여 지적 충격을 극대화.

| Scene | 내용/핵심 시각 자료 | 프롬프트 타입 및 핵심 키워드 | 예시 Midjourney Prompt (수채화풍) |
| :---: | :--- | :--- | :--- |
| **S-04** | 지자기 변화 분석 (시간의 왜곡) | **[Data Interface/Diagram]** 지구 자기장의 시간적 변화를 보여주는 복잡한 곡선 그래프와 나침반. 배경에 양피지 질감과 글리치 효과가 오버레이됨. | `Watercolor visualization of the Earth's fluctuating magnetic field over time (paleomagnetism graph). Incorporate vintage data overlay UI elements and a compass rose. The image must look like an archival scientific diagram with subtle glitch effect --ar 16:9` |
| **S-05** | 공식 기록의 공백(지식의 누락) | **[Artifact/Contrast]** 완벽하게 보존된 고문서와, 그 사이에 의도적으로 '빈 공간' 또는 '균열'을 넣어 정보가 빠진 느낌을 주는 대비적 구도. | `A close-up watercolor shot of a meticulously preserved ancient manuscript page (parchment). A noticeable section in the center is deliberately empty or covered by a crack/void effect, suggesting missing information. High tension and intellectual mystery. --ar 16:9` |

---
**[자가평가]** 완료 — B단계 아웃라인에 맞춰 모든 세그먼트의 목적과 분위기를 반영한 일관된 비주얼 시스템(수채화풍)과 구체적인 프롬프트 템플릿을 제시했으므로, 다음 단계인 '실제 이미지 생성' 준비가 완료되었습니다.
**[다음 단계]** 대기 — Researcher/Writer에게 최종 스크립트와 아웃라인이 확정된 후, 이 가이드라인에 따라 실제 '이미지 배치 및 템플릿 디자인 (Figma)'을 요청해야 합니다.
