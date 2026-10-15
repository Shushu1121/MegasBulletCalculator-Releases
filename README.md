# Megas Bullet Calculator

**Megas Bullet Calculator**는 Astral Party의 PvE에서 **메가스**를 플레이할 때 손패, 포격 예상 피해, 다음 라운드 예상 손패, 포격 대상 후보를 표시하는 Windows용 비공식 보조 오버레이입니다.

## 다운로드

최신 버전: **v1.1.1** — 2026년 10월 15일 게임 업데이트 이후 발생한 UI 미표시 문제 수정

**[최신 버전 다운로드 (GitHub Releases)](https://github.com/Shushu1121/MegasBulletCalculator-Releases/releases/latest)**

## 시연 영상

[![Megas Bullet Calculator v1.1.0 시연 영상](https://img.youtube.com/vi/YkWcCwN0-Iw/maxresdefault.jpg)](https://youtu.be/YkWcCwN0-Iw)

## 주요 기능

- **상단 HUD:** 현재 손패 장수, 배틀 카드 코스트 합계, 예상 포격 횟수·피해량, 현재 라운드 및 다음 라운드 예상 손패 표시
- **상세 정보:** 포격 계산 내역과 다음 라운드 손패 예측을 필요할 때 펼쳐 확인
- **우측 사이드 UI:** 전투·상점 등 게임 상황에 맞춰 계산 정보를 표시하는 접이식 패널
- **포격 대상 표시:** 스킬 착지 발판을 선택할 때 유효한 적을 표적 마크로 표시하고, 화면 밖 대상은 방향으로 안내
- **포격 범위 표시:** 선택한 발판 기준 미사일 아이콘과 거리 `+N` 표시 (선택 기능)
- **편의 기능:** UI 표시 방식·투명도 조절, 카메라 이동 중 표적 숨기기, 한국어·영어(English)·일본어(日本語)·중국어(中文) 지원
- **자동 실행·종료:** 메가스로 PvE 게임에 진입하면 실행되고 해당 판이 종료되면 함께 종료

> **포격 대상 표시는 실제 명중할 적을 확정적으로 예측하는 기능이 아닙니다.** 포격 대상으로 선택될 수 있는 후보를 표시하며, 실제 공격 대상은 후보 중 무작위로 결정됩니다.

## 설치 및 실행

1. [Releases](https://github.com/Shushu1121/MegasBulletCalculator-Releases/releases/latest)에서 `MegasBulletCalculator_v1.1.1_Windows.zip`을 다운로드하고 압축을 해제합니다.
2. Astral Party를 종료한 상태에서 `dist` 폴더의 `MegasBulletCalculator.exe`를 한 번 실행합니다.
3. 필요한 BepInEx 및 Megas Bullet Sensor가 자동으로 설치·설정됩니다.
4. 이후 잠재능력을 해금한 **메가스로 PvE 게임에 진입**하면 Calculator가 자동 실행됩니다.

처음 설치하는 경우 게임 시작이 평소보다 오래 걸릴 수 있습니다.

## 조작 및 단축키

단축키는 Astral Party가 활성화된 상태에서 사용할 수 있습니다.

| 키 | 기능 |
|---|---|
| `Z` | 누르는 동안 현재 손패·포격 상세 정보 표시 |
| `X` | 누르는 동안 다음 라운드 손패 상세 정보 표시 |
| `C` | 누르는 동안 우측 사이드 UI 펼치기 |
| `V` | 미사일 아이콘 및 발판 거리 `+N` 표시 ON/OFF |
| `B` | Calculator 및 표적 오버레이 표시/숨김 |

상단 HUD 패널을 클릭하면 상세 정보를 고정할 수 있으며, 우측 사이드 UI는 탭을 클릭해 펼치거나 접을 수 있습니다.

## 설정

Windows **시스템 트레이의 Megas Bullet Calculator 아이콘을 우클릭**하면 설정을 변경할 수 있습니다.

**UI 표시 방식**

- **혼합 사용 (기본값):** 상황에 따라 상단 HUD와 우측 사이드 UI를 사용
- **HUD UI만 사용:** 상단 HUD 중심으로 표시
- **우측 사이드 UI만 사용:** 우측 사이드 UI 중심으로 표시

이 밖에도 UI 투명도, 표적 마크, 포격 범위 표시, 카메라 이동 중 표적 숨김, 언어 등을 설정할 수 있습니다.

## 지원 환경

- **운영체제:** Windows 10 / 11
- **게임:** Astral Party Steam Global/INT, PvE
- **캐릭터:** 잠재능력을 해금한 메가스
- **권장 화면:** 주 모니터 전체화면, 1920×1080 (16:9)

창모드는 지원하지 않습니다. 다른 해상도, 화면 배율 또는 다중 모니터 구성에서는 일부 화면 표시가 정확하지 않을 수 있습니다. PvP는 지원·검증 대상이 아닙니다.

**Shushu Shield Indicator와 함께 사용할 수 있습니다.**

## 제거 방법

1. Astral Party와 Calculator를 종료합니다.
2. `dist` 폴더의 `MegasBulletCalculator_Uninstall.exe`를 실행합니다.
3. 제거가 완료되면 압축을 해제했던 `dist` 폴더를 삭제합니다.

제거 프로그램은 다른 도구에서 사용 중인 BepInEx 및 플러그인을 보존하도록 설계되어 있습니다.

## 이용 및 배포 안내

Megas Bullet Calculator는 Astral Party 개발사 또는 배급사의 **공식 제품이 아닙니다.** 게임의 이용약관 및 운영정책을 확인한 뒤 사용해 주세요.

이 도구는 게임 플레이를 보조하는 정보를 표시하며, 자동 입력·자동 플레이·게임 데이터 변경 기능을 제공하지 않습니다. Sensor와 Calculator 간 정보 전달은 사용자 PC 내부에서 이루어집니다.

프로그램은 원제작자가 정한 비상업적 이용·배포 조건에 따라 제공됩니다. 원본 ZIP을 수정하지 않고 출처를 명시한 비상업적 공유는 허용되지만, 상업적 이용이나 무단 수정본의 공개 재배포 등은 제한됩니다. 자세한 내용은 [LICENSE.txt](LICENSE.txt)를 확인하세요.

제3자 구성요소의 라이선스는 배포 파일의 `THIRD_PARTY_NOTICES.txt` 및 `LICENSES` 폴더를 따릅니다. 게임의 캐릭터·이미지·명칭 등 게임 자산의 권리는 각 권리자에게 있습니다.

## Credits

**렌이좋은데슈슈쉴드자꾸날려먹어서답답했던아붕이**
