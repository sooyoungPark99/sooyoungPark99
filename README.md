# Sooyoung Park | Oracle DBA

Oracle 데이터베이스 설치 및 운영 환경 구축 경험을 기록합니다.

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

## Oracle 주요 학습 내용

### Admin
- Linux 7.9/8.9 환경에서 Oracle 12c / 19c / 26ai 멀티 버전 설치
- DBCA / Command Line / 수동 방식으로 DB 생성 및 삭제 후 재생성
- Docker 기반 Oracle 26ai 구동
- Control file 다중화 및 손상 복구 / Redo log 그룹 추가 및 미러링
- Tablespace 생성 및 공간 관리 / User 생성 및 권한 관리
- Alert log / Trace 파일 분석 기반 장애 원인 특정
- AWR 리포트 4종 생성 및 분석

### Backup & Recovery
- Close(Cold) / Open(Hot) Backup 및 Hot Backup 중 장애 복구
- Export / Datapump / SQL*Loader 활용한 백업
- RMAN 백업: Backup Set / Image Copy / Incremental / 압축 / 암호화
- Recovery Catalog 구축 및 운영
- 모든 파일(Datafile / Controlfile / Redo log / Spfile) 삭제 후 전체 복구
- 불완전 복구: Time base / Cancel base (일반 환경 + ASM 환경)
- Flashback Database / 블록 손상 복구 / Clone DB 구축
- Log Miner를 이용한 시점 특정 및 불완전 복구

### RAC
- VirtualBox 환경에서 2노드 RAC 클러스터 직접 구축
- Grid Infrastructure / 공유 스토리지 / ASM 디스크 그룹 구성
- srvctl 명령어 활용 및 Switchover / Failover 테스트
- RAC 환경 백업 및 복구 / Recovery Catalog 연동

### Tuning
- 옵티마이저 실행계획 해석 및 인덱스 / 조인 방식별 I/O 비교 분석
- Explain Plan / Autotrace / SQL Trace / TKPROF / AWR 활용
- 바인드 변수 최적화 / Result Cache / PL/SQL 튜닝

### Data Guard
- Primary / Standby DB 구성 및 Redo 동기화
- Switchover / Failover 역할 전환 테스트
- DGMGRL Broker를 활용한 자동화 구성

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

