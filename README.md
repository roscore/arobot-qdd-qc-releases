# ARobot QDD QC

QDD 모터 품질 검사 프로그램 / QDD Motor Quality Control Program

---

## 한국어

### 다운로드

최신 버전을 [Releases](https://github.com/roscore/arobot-qdd-qc-releases/releases/latest) 페이지에서 다운로드하세요.

| 플랫폼 | 파일 | 설명 |
|--------|------|------|
| Windows | `ARobot_QDD_QC_Setup_*.exe` | **설치 프로그램 (권장)** |
| Windows | `ARobot_QDD_QC_Windows.zip` | 포터블 버전 |
| Windows | `ARobot_QDD_QC.exe` | 단독 실행 파일 |
| Linux | `ARobot_QDD_QC_Linux.tar.gz` | 설정 포함 전체 패키지 |
| Linux | `arobot_qdd_qc` | 단독 실행 파일 |

### 빠른 시작

**Windows (권장):**
1. Releases 페이지에서 `ARobot_QDD_QC_Setup_*.exe` 다운로드
2. 설치 프로그램 실행
3. 화면 안내에 따라 설치 완료
4. 바탕화면 또는 시작 메뉴에서 프로그램 실행

**Windows (포터블):**
1. `ARobot_QDD_QC_Windows.zip` 다운로드
2. 원하는 폴더에 압축 해제
3. `ARobot_QDD_QC.exe` 더블클릭하여 실행

**Linux:**
```bash
wget https://github.com/roscore/arobot-qdd-qc-releases/releases/latest/download/ARobot_QDD_QC_Linux.tar.gz
tar -xzvf ARobot_QDD_QC_Linux.tar.gz
cd arobot_qdd_qc_linux
./arobot_qdd_qc
```

### 사용 방법

1. USBCAN 어댑터를 컴퓨터에 연결
2. CAN 케이블로 QDD 모터 연결
3. 프로그램 실행 후 [연결] 버튼 클릭
4. 모델 선택 후 [QC 시작] 버튼 클릭
5. 테스트 완료 후 결과 확인 (PASS/FAIL, 등급 A/B/F)

### 하드웨어 요구사항

- USBCAN 어댑터 (USBCAN2)
- QDD 모터 (X4-10, X4-36, X6-60, X8-120, X12-320)
- CAN 버스 케이블

### 등급 기준

| 등급 | 전류 편차 | 결과 |
|------|----------|------|
| A | ≤ 0.01A | 합격 (최상) |
| B | 0.01A ~ 0.5A | 합격 (양호) |
| F | > 0.5A | 불합격 |

### 자동 업데이트

프로그램 시작 시 자동으로 새 버전을 확인합니다. 새 버전이 있으면 업데이트 알림이 표시됩니다.

---

## English

### Download

Download the latest version from [Releases](https://github.com/roscore/arobot-qdd-qc-releases/releases/latest) page.

| Platform | File | Description |
|----------|------|-------------|
| Windows | `ARobot_QDD_QC_Setup_*.exe` | **Installer (Recommended)** |
| Windows | `ARobot_QDD_QC_Windows.zip` | Portable version |
| Windows | `ARobot_QDD_QC.exe` | Standalone executable |
| Linux | `ARobot_QDD_QC_Linux.tar.gz` | Full package with config |
| Linux | `arobot_qdd_qc` | Standalone executable |

### Quick Start

**Windows (Recommended):**
1. Download `ARobot_QDD_QC_Setup_*.exe` from Releases page
2. Run the installer
3. Follow the on-screen instructions
4. Launch from desktop or Start menu

**Windows (Portable):**
1. Download `ARobot_QDD_QC_Windows.zip`
2. Extract to desired folder
3. Double-click `ARobot_QDD_QC.exe` to run

**Linux:**
```bash
wget https://github.com/roscore/arobot-qdd-qc-releases/releases/latest/download/ARobot_QDD_QC_Linux.tar.gz
tar -xzvf ARobot_QDD_QC_Linux.tar.gz
cd arobot_qdd_qc_linux
./arobot_qdd_qc
```

### Usage

1. Connect USBCAN adapter to computer
2. Connect QDD motor via CAN cable
3. Run program and click [Connect] button
4. Select model and click [Start QC] button
5. Check results after test (PASS/FAIL, Grade A/B/F)

### Hardware Requirements

- USBCAN adapter (USBCAN2)
- QDD motor (X4-10, X4-36, X6-60, X8-120, X12-320)
- CAN bus cable

### Grade Criteria

| Grade | Current Deviation | Result |
|-------|-------------------|--------|
| A | ≤ 0.01A | PASS (Excellent) |
| B | 0.01A ~ 0.5A | PASS (Good) |
| F | > 0.5A | FAIL |

### Auto Update

The program automatically checks for updates on startup. You'll be notified when a new version is available.

---

## Support / 지원

문제가 있으시면 Issues 페이지에 문의해 주세요.
For issues, please visit the Issues page.

---

**Copyright (C) 2024 ARobot. All rights reserved.**
