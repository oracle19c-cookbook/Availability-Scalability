## 소개

---

Active Data Guard는 오라클 데이터 복제 솔루션입니다.
복제된 StandbyDB는 read only mode 상황애서 read only 전용 업무 (reporting)를 수행하여 
Primary DB의 부하를 분산 시킬수 있습니다.
Oracle 19c ADG는 복제된 StandbyDB에 dml session 이 들어 오면 이를 primary로 redirect하여 수행하는 기능이 추가되었습니다.

![](https://github.com/oracle19c-cookbook/Availability-Scalability/blob/master/AciveDataGuard/adg.JPG)

## Hands-On

#### 19c ADG DML Redirect 

- [19c ADG DML Redirect](https://github.com/oracle19c-cookbook/Availability-Scalability/blob/master/AciveDataGuard/19c_ADG_DML_Redirect.pdf)

## 참고 자료

- 공식 매뉴얼
    - [Performing DML Operations on Active Data Guard Standby Databases ](https://docs.oracle.com/en/database/oracle/oracle-database/19/sbydb/managing-oracle-data-guard-physical-standby-databases.html#GUID-8AAD002C-ED06-4349-8BB5-EC8DB30B2628)
- White Papaper 
    - [Oracle (Active) Data Guard 19c](https://www.oracle.com/technetwork/database/availability/dg-adg-technical-overview-wp-5347548.pdf)

