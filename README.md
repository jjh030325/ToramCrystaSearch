
# 0. 서비스 URL 주소
서비스 링크 : (https://asicrystasearch.netlify.app/)

<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
- 프로젝트 이름: ToramCrystaSearch
- 프로젝트 설명: 토람온라인이라는 게임의 크리스타라는 아이템 검색 웹 서비스입니다. 기존에도 크리스타 검색기는 존재하였으나 몇 년간 업데이트가 없어 최신 크리스타 검색이 불가능하다는 문제점이 존재하였습니다. 때문에 이후로도 꾸준히 활용될 수 있도록 해당 크리스타 검색기에서 영감을 받아 해당 프로젝트를 시작하게 되었습니다.

<br/>
<br/>

# 2. Key Features (주요 기능)
- **이름 검색**:
  - 찾는 크리스타의 이름을 입력하여 검색하고, 해당 크리스타의 정보를 확인할 수 있습니다.

- **영역 검색**:
  - 찾는 크리스타가 어떤 부위에 적용할 수 있는 크리스타인지 직관적인 필터링을 통해 원하는 정보를 쉽게 파악할 수 있습니다.

- **옵션 검색**:
  - 찾는 옵션을 선택하고, 연산자와 수치를 선택해 특정 범위 내의 옵션 수치를 가지는 크리스타를 쉽게 찾을 수 있습니다.

- **지속적인 업데이트**:
  - 현재 적용되지 않은 크리스타들과 추가적으로 필요한 기능을 꾸준한 업데이트를 통해 제작하고 있습니다.

<br/>
<br/>

# 3. Technology Stack (기술 스택)
## 3.1 Language
|  |  |
|-----------------|-----------------|
| HTML    |<img src="https://github.com/user-attachments/assets/2e122e74-a28b-4ce7-aff6-382959216d31" alt="HTML" width="100">| 
| CSS    |   <img src="https://github.com/user-attachments/assets/c531b03d-55a3-40bf-9195-9ff8c4688f13" alt="CSS" width="100">|
| Javascript    |  <img src="https://github.com/user-attachments/assets/4a7d7074-8c71-48b4-8652-7431477669d1" alt="Javascript" width="100"> | 

<br/>
<br/>

# 4. Project Structure (프로젝트 구조)
```plaintext
project/
├── CrystaData/
│   ├── armor.json              # 방어구 크리스타 JSON 데이터
│   ├── enhanced_armor.json     # 방어구 강화 크리스타 JSON 데이터
│   ├── enhanced_hat.json       # 추가장비 강화 크리스타 JSON 데이터
│   ├── enhanced_normal.json    # 노말 강화 크리스타 JSON 데이터
│   ├── enhanced_ring.json      # 특수장비 강화 크리스타 JSON 데이터
│   ├── enhanced_weapon.json    # 무기 강화 크리스타 JSON 데이터
│   ├── hat.json                # 추가장비 크리스타 JSON 데이터
│   ├── normal.json             # 노말 크리스타 JSON 데이터
│   ├── ring.json               # 특수장비 크리스타 JSON 데이터
│   └── weapon.json             # 무기 크리스타 JSON 데이터
├── CrystaImg/
│   ├── armor.png               # 방어구 크리스타 이미지
│   ├── enhanced_armor.png      # 방어구 강화 크리스타 이미지
│   ├── enhanced_hat.png        # 추가장비 강화 크리스타 이미지
│   ├── enhanced_normal.png     # 노말 강화 크리스타 이미지
│   ├── enhanced_ring.png       # 특수장비 강화 크리스타 이미지
│   ├── enhanced_weapon.png     # 무기 강화 크리스타 이미지
│   ├── hat.png                 # 추가장비 크리스타 이미지
│   ├── normal.png              # 노말 크리스타 이미지
│   ├── ring.png                # 특수장비 크리스타 이미지
│   └── weapon.png              # 무기 크리스타 이미지
├── index.html                  # HTML 파일
├── style.css                   # CSS 파일
└── README.md                   # 프로젝트 개요
```

<br/>
<br/>

# 5. Reference (참고)
- 크리스타 이미지 데이터와 옛날부터 존재하던 크리스타 데이터 참고 : (https://github.com/toramcalculator/crysta)
