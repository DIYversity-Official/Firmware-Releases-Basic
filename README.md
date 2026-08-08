# DIYversity Basic — 공식 펌웨어 릴리스

DIYversity 스마트 라인조명(Basic 라인)의 정식 펌웨어 배포 저장소입니다.
이 저장소는 **배포 전용**이며, 소스 코드 저장소가 아닙니다.

## 업데이트 방법

제품 화면(웹/앱)의 **설정 → 펌웨어 → 업데이트** 버튼을 누르면 기기가 이
저장소의 최신 버전을 확인하고, 사용자가 승인하면 자동으로 적용합니다.
별도의 파일 다운로드나 수동 설치는 필요하지 않습니다.

> ⚠️ 수동 플래싱은 권장하지 않습니다. 잘못된 설치로 기기가 동작 불능이
> 될 수 있으며, 이 경우 지원 대상에서 제외될 수 있습니다.

## 저장소 구성

| 파일 | 설명 |
|---|---|
| `firmware.bin` | 최신 정식 펌웨어 (기기 업데이트가 사용하는 원본) |
| `version.json` | 기기가 읽는 버전 메타데이터 — **임의 수정 금지** |
| Releases | 버전별 보관본과 변경 사항 |

## 오픈소스 고지 (Open Source Notice)

이 펌웨어는 **MIT 라이선스로 배포되던 시기의 [WLED](https://github.com/wled/WLED)
프로젝트를 기반**으로, DIYversity 제품을 위한 기능을 더해 제작되었습니다.
훌륭한 토대를 만들어 주신 WLED와 기여자 여러분께 감사드립니다.

This firmware is based on the WLED project as licensed under the MIT
License, with additional proprietary functionality for DIYversity products.
See [LICENSE](LICENSE) for the applicable license text.

포함된 오픈소스 구성요소(WLED 및 관련 Arduino/ESP32 라이브러리)의 라이선스는
각 프로젝트의 라이선스를 따릅니다.

본 펌웨어는 "있는 그대로(AS IS)" 제공되며, 상품성이나 특정 목적 적합성에
대한 어떠한 보증도 하지 않습니다.

## 문의

biz@diyversity.co.kr
