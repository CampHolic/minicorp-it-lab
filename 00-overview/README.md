# MiniCorp IT Lab Overview

MiniCorp IT Lab 프로젝트의 전체 계획과 설계 내용을 기록합니다.

## Contents

- 프로젝트 목적 : 중소기업 IT 인프라 환경을 가상으로 구축하고 운영과 azure 구성을 통해 universal print까지 해보는 개인 실습 프로젝트입니다.
- MiniCorp 회사 구조 : 
- IT 인프라 구성 : On-Prem AD → Entra ID → Universal Print → Intune 실무 구축 프로젝트
- VMware 구성도:
                   [HOST PC]
                       │
                       │
                  가상 네트워크
                       │
                [Windows Server 2025 ]
                       │
          ┌────────────┴────────────┐
          │                         │
       AD DS                     DNS/DHCP
          │
          ↓
    Hybrid 환경 실습
          │
          ↓
      Entra ID 연계
          │
          ↓
   Universal Print 실습

  
- universal print 구성도:
  
                      Microsoft Cloud
                         │
                    Microsoft Entra ID
                         │
                  Universal Print
                         │
              ┌──────────┴──────────┐
              │                     │
        Printer/Device          사용자 PC
              │                     │
          복합기 ←────────────── Windows






- 학습 로드맵
- 
   | 주차 | 핵심 주제             | 결과물                      |
| -- | ----------------- | ------------------------ |
| 1주 | AD / DNS / GPO 복습 | 사내 도메인 구축                |
| 2주 | 사용자·그룹·권한·GPO     | 부서별 정책 구축                |
| 3주 | 네트워크 + Wireshark  | 네트워크 장애 분석               |
| 4주 | Entra ID          | On-Prem → Cloud Identity |
| 5주 | Universal Print   | 클라우드 프린팅 구축              |
| 6주 | Intune            | PC/프린터 정책 배포             |
| 7주 | 장애 대응             | 실전 Troubleshooting       |
| 8주 | 종합 프로젝트           | 고객사 구축 보고서 + 포트폴리오       |



- 프로젝트 진행 현황
  2026-09-18_VMware 설치 및 window server 2025설치와 네트워크 IP할당 완료
  
