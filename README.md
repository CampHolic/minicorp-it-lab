# 🏢 MiniCorp IT Lab

VMware 기반 가상 회사 환경을 구축하고 운영하면서
Windows Server, Active Directory, 네트워크, 보안 및
IT 인프라 운영 역량을 학습하고 기록하는 개인 프로젝트입니다.

---

## 🎯 Project Goal

실제 기업의 IT 인프라 환경을 가상으로 구축하고 운영하면서
다음과 같은 실무 역량을 단계적으로 학습하는 것을 목표로 합니다.

- Windows Server 관리
- Active Directory 관리
- 사용자 및 그룹 관리
- Group Policy 관리
- DNS / DHCP 구성
- Windows Client 도메인 관리
- 네트워크 문제 해결
- 보안 정책 적용
- PowerShell 자동화
- IT 인프라 장애 대응

---

## 🏢 MiniCorp

MiniCorp는 IT 인프라 실습을 위해 만든 가상의 중소기업입니다.

### Departments

- Management
- Sales
- Engineering
- HR
- IT

---

## 🖥️ Lab Environment

| Component | Environment |
|---|---|
| Hypervisor | VMware Workstation |
| Server | Windows Server |
| Client | Windows 11 |
| Directory Service | Active Directory |
| DNS | Windows DNS |
| DHCP | Windows DHCP |
| Policy | Group Policy |
| Automation | PowerShell |

---

## 🌐 Network

MiniCorp의 가상 네트워크 환경을 구성하고
서버와 클라이언트 간 통신을 실습합니다.

예정 구성:

```text
                Internet
                   │
              [ Router ]
                   │
             192.168.10.0/24
                   │
        ┌──────────┴──────────┐
        │                     │
 [ Windows Server ]      [ Windows 11 ]
    192.168.10.10          Client01
        │
        ├── Active Directory
        ├── DNS
        └── DHCP

