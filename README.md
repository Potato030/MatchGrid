<div align="center">

# 🏟️ 매치그리드 · MatchGrid

**팔로우하는 팀과 리그의 경기만, 내 캘린더에.**

Android 8.0+ · 기기 시간대 또는 직접 선택 · 한국어 / English

### [매치그리드 1.5.0 다운로드](https://potato030.github.io/MatchGrid/MatchGrid-24.apk)

</div>

---

## 매치그리드로 할 수 있는 일

- **내 경기 캘린더** — 관심 팀이나 리그를 선택하면 해당 경기만 월간 달력에 표시됩니다. 날짜를 누르면 대진과 시작 시간을 확인할 수 있습니다.
- **홈 화면 위젯** — 앱을 열지 않아도 월간 일정을 보고, 날짜를 눌러 경기 목록으로 이동할 수 있습니다.
- **읽기 편한 일정** — 펼친 달력과 위젯에서 대진을 두 줄로 표시하고, 더 있는 경기는 별도의 `+N경기`로 알려드립니다. F1은 GP 이름과 세션을 나눠 표시합니다.
- **경기 검색** — 돋보기에서 팔로우한 저장 일정을 팀명·대회·날짜로 찾고, 결과를 눌러 그날의 상세 일정으로 이동합니다.
- **밝게 · 어둡게 · 기기 설정 따름** — 설정에서 고른 화면 테마를 앱과 위젯에 함께 적용합니다.
- **손끝으로 넘기는 달력** — 아래로 끌면 경기명이 표시되는 전체 달력, 위로 끌면 상세 일정이 펼쳐집니다. 달력은 월별로, 상세 일정은 하루씩 좌우로 넘길 수 있습니다.
- **자동 동기화** — 공개 일정을 약 6시간마다 갱신합니다. 바로 새로고침하려면 **설정 → 일반 설정 → 일정 동기화**를 누르세요.
- **동기화 상태 확인** — 설정에서 진행·대기·실패 상태와 마지막 전체 성공 시간을 확인하고, 종목별 마지막 성공 시간도 볼 수 있습니다. 실패한 출처의 기존 일정은 유지합니다.
- **경기 시작 전 알림** — 팔로우한 경기의 시작 10분·30분·60분 전에 알려드립니다. 기본은 꺼짐이며 **설정 → 알람 → 메시지 알림**에서 켤 수 있습니다. 알림을 누르면 해당 날짜의 상세 일정으로 이동합니다.

## 지원 일정

| 종목 | 리그 및 대회 |
| --- | --- |
| ⚽ 축구 | 프리미어리그 · UEFA 챔피언스리그 |
| 🏀 농구 | NBA |
| 🏎️ 모터스포츠 | F1 · 프랙티스, 퀄리파잉, 스프린트, 레이스 |
| 🎮 리그 오브 레전드 | LCK · LPL · LEC · LCS · LCP · CBLOL · First Stand · MSI · Worlds |
| 🎯 발로란트 | VCT Pacific · Americas · EMEA · China · Masters · Champions |

공식 1부 지역 리그와 국제 대회의 공개 일정을 수집합니다. 발로란트의 Challengers·Ascension·승격 예선·비시즌 대회는 제외하고, 여러 캘린더에 겹치는 경기는 하나로 합칩니다. 달력에는 팔로우한 경기만 표시되며, 공개 출처에 아직 올라오지 않은 경기는 표시할 수 없습니다.

## 처음 사용하기

1. Android 기기에 위 APK를 설치합니다.
2. 앱의 **설정 → 리그 추가**에서 리그를 누른 뒤, 상단 검색창과 팀별 스위치로 관심 팀을 선택합니다. **선택한 팀만**을 켜면 개별 팔로우 팀을 모아 볼 수 있습니다. F1은 스위치 하나로 선택하고, LoL은 대회 구분 없이 하나로 관리합니다. 선택하기 전에는 빈 달력이 보입니다.
3. 홈 화면에 위젯을 추가하려면 빈 공간을 길게 누르고 **위젯 → 매치그리드**를 선택합니다.

경기 알림을 켜면 필요한 시스템 권한을 안내합니다. Android 13 이상에서는 알림 허용, Android 12 이상에서는 ‘알람 및 리마인더’ 허용이 필요합니다. 저장된 일정으로 알림을 예약하며, 일정 동기화와 관심 항목 변경 후 예약을 갱신합니다. 기기를 끄거나 앱을 강제 종료한 동안에는 알림이 오지 않을 수 있습니다.

**설정 → 일반 설정**에서 시간대 자동 설정을 끄면 나타나는 **시간대 수동 설정**에서 `(UTC+09:00) 서울` 같은 Windows식 지역 이름을 선택할 수 있습니다. 도시 이름과 UTC 오프셋으로 검색할 수 있고, 실제 경기 시각에는 날짜별 서머타임을 적용합니다.

## 앱 업데이트

### 최신 버전 · v1.5.0

**APK SHA-256**

`0a9a4c8db18d84ca25b2a20ef986c030b5318a7eb700e167f69da22583bacd96`

**변경 내역**

- 빈 달력의 이유를 관심 항목 미선택·해당 날짜 경기 없음·일정 불러오는 중·불러온 일정이 없는 기간·동기화 실패로 구분합니다. 관련 출처의 갱신 실패는 상단에서 설정으로 바로 확인할 수 있습니다.
- 펼친 달력과 위젯의 경기명을 두 줄로 표시하고 추가 경기 수를 별도로 표시합니다. 위젯 크기에 따라 표시량을 조절합니다.
- 연도·월과 오늘 버튼을 상단에 항상 표시하고, 한국어 날짜 선택창과 팝업 스타일을 개선했습니다.
- 팀 선택 화면에 선택한 팀 필터를 추가하고, 목록을 스크롤해도 뒤로 가기와 검색창을 유지합니다.
- 앱·위젯에 밝게·어둡게·기기 설정 따름 테마를 추가했습니다.
- 팔로우한 저장 경기를 팀명·대회·날짜로 검색하고 해당 날짜로 이동할 수 있습니다.
- LoL 6개 지역 리그와 국제 대회, 발로란트 4개 지역 리그와 국제 대회로 수집 범위를 확대했습니다. 발로란트 하위 대회·예선을 제외하고 중복 경기를 합칩니다.

<details>
<summary>이전 버전 변경 내역 보기</summary>

| 버전 | 변경 내역 |
| --- | --- |
| [**1.4.16**](https://potato030.github.io/MatchGrid/archive/MatchGrid-23.apk) | LoL 경기 단계와 팀 이름 분리, e스포츠 지역별 접기·펼치기와 중계 약어·공식 팀 로고 |
| [**1.4.15**](https://potato030.github.io/MatchGrid/archive/MatchGrid-22.apk) | 일반 설정 하위 메뉴, 시간대 자동·수동 전환과 마지막 선택 기억 |
| [**1.4.14**](https://potato030.github.io/MatchGrid/archive/MatchGrid-21.apk) | 리그·팀 선택 하위 메뉴, LoL 통합, Windows식 시간대 목록 |
| [**1.4.13**](https://potato030.github.io/MatchGrid/archive/MatchGrid-20.apk) | 알람 상세 메뉴와 경기 시작 전 알림, 동기화 상태, 월 화살표 제거와 종목별 점 표시 |
| [**1.4.12**](https://potato030.github.io/MatchGrid/archive/MatchGrid-19.apk) | 경기 박스 라운드와 여백, 상세 일정 로고, 설정 아이콘 개선 |
| [**1.4.11**](https://potato030.github.io/MatchGrid/archive/MatchGrid-18.apk) | 상하 패널의 짧은 스와이프 개선 유지, 좌우 넘기기 인식 시간 복원 |
| [**1.4.10**](https://potato030.github.io/MatchGrid/archive/MatchGrid-17.apk) | 짧은 상하·좌우 스와이프 인식 시간 확대 |
| [**1.4.9**](https://potato030.github.io/MatchGrid/archive/MatchGrid-16.apk) | 회색 날짜 슬라이드, 달력 전환 끊김 개선, 빠른 좌우 스와이프, 다음 관심 경기 카드 및 시간대 접미사 제거 |
| [**1.4.8**](https://potato030.github.io/MatchGrid/archive/MatchGrid-15.apk) | 달력 펼치기·접기, 월·날짜 드래그 전환, NBA 위젯 3글자 약어 |
| [**1.4.7**](https://potato030.github.io/MatchGrid/archive/MatchGrid-14.apk) | 회색으로 표시되는 이전·다음 달 날짜를 누르면 해당 월로 이동 |
| [**1.4.6**](https://potato030.github.io/MatchGrid/archive/MatchGrid-13.apk) | 요일 아래 구분선이 날짜 칸을 가리는 문제 수정 |
| [**1.4.5**](https://potato030.github.io/MatchGrid/archive/MatchGrid-12.apk) | 업데이트 주소 설정 제거 및 달력과 일정 목록 분리 |
| [**1.4.4**](https://potato030.github.io/MatchGrid/archive/MatchGrid-11.apk) | 설치 화면의 앱 이름에 버전 표시 |
| [**1.4.3**](https://potato030.github.io/MatchGrid/archive/MatchGrid-10.apk) | 기기 시간대 기본 적용 및 앱·위젯 시간대 선택 추가 |
| [**1.4.2**](https://potato030.github.io/MatchGrid/archive/MatchGrid-9.apk) | 공개 일정 출처 고정, 수동 동기화 및 업데이트 검증 보강 |
| **1.4** | 앱 내 업데이트 확인, APK 해시·서명 검증 추가 |
| **1.3.2** | 날짜를 누르면 달력 격자를 유지하고 선택 표시와 일정 목록만 갱신 |
| **1.3.1** | 월 경계 날짜를 눌러도 보고 있던 월을 유지 |
| **1.3** | 한국어 대진 표기와 F1 세션 이름 개선 |
| **1.2** | 매치그리드 이름과 아이콘 적용, 선택한 리그와 팀 일정만 표시 |
| **1.1** | 키 없는 일정 갱신, 월간 위젯과 한국어·영어 설정 추가 |

</details>

---

이 저장소는 매치그리드의 설치 및 업데이트 파일을 제공합니다. 경기 일정은 공개 데이터 출처의 편성에 따라 달라질 수 있습니다.

### 일정 출처 및 권리 안내

<sub>프리미어리그·UEFA 챔피언스리그·NBA: <a href="https://www.espn.com/">ESPN</a> · F1: <a href="https://github.com/jolpica/jolpica-f1/blob/main/TERMS.md">Jolpica-F1</a> (<a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a>, 설정한 시간대로 변환하여 표시) · LoL: <a href="https://www.tompka.io/lol-events/">LoL Events</a> · 발로란트: <a href="https://valorant-calendar.mizt.ch/">Valorant Match Schedule</a></sub>

<sub>매치그리드는 경기 일정을 편하게 확인하기 위해 독립적으로 제작한 무료·비상업적 팬 프로젝트입니다. 리그, 구단, 게임 및 데이터 제공사와 별개로 운영됩니다. 명칭, 로고 및 상표에 대한 권리는 각 권리자에게 있으며, 일정 데이터에는 각 출처의 이용 조건이 적용됩니다. 출처나 권리 관련 문의는 <a href="https://github.com/Potato030/MatchGrid/issues">GitHub Issues</a>에 남겨 주세요.</sub>

<sub>LoL·발로란트 팀 소속과 로고: <a href="https://lolesports.com/en-US/gpr/2026/current">LoL Esports</a> · <a href="https://valorantesports.com/en-US/gpr/2026/current">VALORANT Esports</a> (2026-11-10 확인). 팀 정렬은 국내 인지도를 고려한 기본 배치이며, 공식 인기 순위나 실시간 통계가 아닙니다.</sub>

<sub>일부 Pacific 예선 참가팀의 로고 사본: <a href="https://www.vlr.gg/">VLR.gg</a>. 팀별 원본 주소는 앱에 포함된 출처 안내에 기록했습니다.</sub>
