# Sooyoung Park | Oracle DBA
 
Oracle 데이터베이스 설치 및 운영 환경 구축 경험을 기록합니다.
 
---
 
## 저장소 목록
 
| 저장소 | 설명 |
|--------|------|
| [oracle-19c-rac-install](https://github.com/sooyoungPark99/oracle-19c-rac-install) | Oracle 19c RAC 2노드 설치 가이드 |
| [oracle-19c-asm-install](https://github.com/sooyoungPark99/oracle-19c-asm-install) | ASM 환경 Oracle 19c 설치 가이드 |
| [oracle-19c-dataguard](https://github.com/sooyoungPark99/oracle-19c-dataguard) | Data Guard 구성 및 Switchover / Failover 테스트 |
| [oracle-12c-single-install](https://github.com/sooyoungPark99/oracle-12c-single-install) | Oracle 12c Single Instance 설치 가이드 |
| [oracle-11g-single-install](https://github.com/sooyoungPark99/oracle-11g-single-install) | Oracle 11g Single Instance 설치 가이드 |
| [postgresql-install](https://github.com/sooyoungPark99/postgresql-install) | PostgreSQL 15 설치 및 Oracle 19c 환경 구축 |
| [ora2pg-migration](https://github.com/sooyoungPark99/ora2pg-migration) | Oracle 19c에서 PostgreSQL로 데이터 이행 (Ora2Pg) |
 
---
 
## 역량 소개
 
### Oracle DB 구축·운영
버전·아키텍처별 차이를 이해하고 설치부터 ASM·Grid 연동까지 구축 경험 보유
 
- Oracle 12c / 19c / 26ai 멀티 버전 설치
- CDB·Non-CDB / ASM·Grid Infrastructure 구성
- DBCA / 수동 / Docker 기반 DB 생성
---
 
### 백업·복구·장애 대응
일반 / ASM / RAC 환경에서 전체 파일 삭제, 블록 손상, 패치 장애 등 다양한 장애 시나리오 대응 가능
 
- RMAN: Backup Set / Image Copy / 증분 / 압축 / 암호화
- Datapump / Cold Backup / Hot Backup
- 불완전 복구: Time base / Cancel base / Flashback Database
- Recovery Catalog 구축·운영
---
 
### RAC·Data Guard
RAC 클러스터 구축부터 OCR 복구, Data Guard Switchover·Failover 테스트까지 이중화 환경 전반 구성 경험 보유
 
- VirtualBox 기반 2노드 RAC 클러스터 직접 구축
- ASM 디스크 그룹 / Grid Infrastructure 구성
- Active-Standby Data Guard 구성
- Switchover / Failover / DGMGRL Broker 운영
---
 
### SQL·PL/SQL·튜닝
실행계획 기반 성능 분석 및 PL/SQL 코드 최적화 수행 가능. RAC 환경 캐시퓨전·대기 이벤트 튜닝 경험 보유
 
- 실행계획 해석 / AWR / ADDM 분석
- Explain Plan / Autotrace / SQL Trace / TKPROF 활용
- Range / Hash / List / 복합 파티션 테이블 설계
- PL/SQL 프로시저·트리거·암호화
- RAC 캐시퓨전·대기 이벤트 분석
---
 
### 멀티 DBMS 대응
Oracle 외 오픈소스 DB 환경에서 설치·운영·백업·복구 수행 가능. Ora2Pg 이행 및 PostgreSQL 아카이브 모드 복구 경험 보유
 
- PostgreSQL 15 설치·운영 / Ora2Pg 데이터 이행
- MongoDB CRUD / BSON 데이터 처리 / 백업·복구
- MySQL 테이블 설계 / 데이터 이관
- Hadoop / Hive / Spark 환경 구성
---
 
### Linux 인프라·자동화
Oracle 설치·운영에 필요한 OS 설정, 백업 자동화, alert log 분석 기반 장애 원인 특정 가능
 
- 커널 파라미터 튜닝 (sysctl·limits)
- DBA 셸 스크립트 / 백업 자동화
- crontab / dbms_scheduler 예약 작업
- alert log / trace 파일 분석
---
 
## 기술 스택
 
### Database
 
| 기술 | 내용 |
|------|------|
| Oracle 19c | Single / RAC / ASM / Data Guard / Backup & Recovery / Tuning |
| Oracle 12c | Non-CDB 환경 설치 및 운영 |
| Oracle 11g | Single Instance 설치 및 운영 |
| PostgreSQL 15 | 설치 / 테이블 관리 / Oracle 아키텍처 비교 |
| MongoDB | CRUD / BSON 데이터 처리 / 백업 및 복구 |
 
### Language & Script
 
| 기술 | 내용 |
|------|------|
| SQL | DML/DDL / 다양한 Join / 서브쿼리 / 파티션 테이블 / 실행계획 분석 |
| Python | 데이터 검증 로직 / 로그 파싱 / DB 모니터링 데이터 자동 수집 |
| Shell Script | 백업 자동화 / crontab / dbms_scheduler 예약 작업 |
 
### OS / 도구
 
| 기술 | 내용 |
|------|------|
| Oracle Linux 7.9 / 8.9 | 커널 파라미터 튜닝 / 네트워크 구성 / 시스템 모니터링 |
| VirtualBox 7.0 | 멀티 VM 환경 구성 / RAC 클러스터 구축 |
| Hadoop / Hive / Spark | 분산 파일 시스템 / 빅데이터 파이프라인 구성 |
| 접속 도구 | SQL*Plus / DBCA / NETCA / DBeaver / MobaXterm / PuTTY |
 
---
 
## 진행 중인 학습
 
- Oracle Exadata 스토리지 구조 및 고성능 데이터 처리 아키텍처
- Hadoop / Hive / Spark 빅데이터 파이프라인 구성
 
