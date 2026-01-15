# CPU 이해

## 1. CPU가 하는 일(한 줄)
- CPU는 **명령어를 가져와서(Fetch) → 해석하고(Decode) → 실행(Execute)** 한다.

## 2. 명령어 사이클(Instruction Cycle)
1) Fetch: 메모리에서 명령어 가져오기  
2) Decode: 어떤 명령인지 해석  
3) Execute: 연산/저장/분기 등 실행  
4) (필요 시) Write-back: 결과를 레지스터/메모리에 반영

## 3. 레지스터(Register)
- CPU 내부의 초고속 저장소
- 예시:
  - PC(Program Counter): 다음에 실행할 명령어 주소
  - IR(Instruction Register): 현재 실행 중인 명령어
  - 일반 레지스터: 연산 중간값 저장

## 4. 캐시(Cache)
- CPU와 RAM 속도 차이를 줄이기 위한 중간 저장소
- 지역성(Locality) 덕분에 효과가 큼
  - 시간 지역성 / 공간 지역성

## 5. 오늘의 한 줄 요약
- [예: “CPU는 무조건 메모리에서 명령어를 가져와 사이클로 처리한다.”]