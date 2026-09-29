# 아키박스 PC 자동화 — 설치 파일

[아키박스(archbox.kr)](https://archbox.kr) **PC 자동화**의 Windows 설치 파일을 배포하는 저장소입니다.
소스 코드는 여기에 없습니다. 설치 파일은 [Releases](../../releases/latest)에서 받습니다.

## 설치
1. `Archbox-PC-Agent-Setup-<버전>.exe` 를 받아 실행합니다.
2. 아직 코드 서명 전이라 Windows 가 "Windows의 PC 보호" 경고를 띄울 수 있습니다 — **추가 정보 → 실행**을 누릅니다.
3. 프로그램에서 **아키박스 계정으로 쓰기**를 고르고, 화면의 연결 코드를 포털 [PC 자동화]에서 승인합니다.

## 받은 파일 확인 (선택)
각 릴리스에 적힌 SHA256 값과 비교합니다. PowerShell:

```powershell
Get-FileHash .\Archbox-PC-Agent-Setup-0.2.0.exe -Algorithm SHA256
```

문의: 아키박스 포털 고객센터
