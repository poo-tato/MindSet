# 🌙 Mind Archive

> **"생각을 비우고, 마음을 채우는 고요한 기록 공간"**

복잡한 생각이 머릿속을 떠나지 않을 때, 정제되지 않은 마음을 쏟아낼 수 있는 미니멀 다크 모드 메모장입니다. 

---

## 🎨 Service Flow (서비스 흐름)

```mermaid
graph TD
    Start((접속)) --> Main[메인 화면: 다크 모드]
    Main --> Music[Lofi BGM 선택]
    Main --> Write[기록 시작: 타자기 ASMR]
    
    Write --> Decision{기록의 운명}
    
    Decision -- "간직하기" --> Archive[Local Storage 저장]
    Decision -- "흘려보내기" --> Sand[Sand Mode: 휘발성 삭제]
    
    Archive --> List[프라이빗 아카이브]
    Sand --> End((마음 정돈 완료))
    List --> End

```mindmap
  root((Mind Archive))
    Frontend
      HTML5
      CSS3
      Vanilla JS
    Experience
      Web Audio API (ASMR)
      YouTube IFrame API (BGM)
    Data
      Local Storage (Private)
