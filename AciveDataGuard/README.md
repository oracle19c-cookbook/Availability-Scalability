## 소개

---

Active Data Guard는 오라클 데이터 복제 솔루션입니다.
복제된 StandbyDB는 read only mode 상황애서 read only 전용 업무 (reporting)를 수행하여 
Primary DB의 부하를 분산 시킬수 있습니다.

Oracle 19c ADG는 복제된 StandbyDB에 dml session 이 들어 오면 이를 primary로 redirect하여 수행하는 기능이 추가되었습니다.

![](https://github.com/oracle19c-cookbook/Availability-Scalability/blob/master/AciveDataGuard/adg.JPG)

- 오라클Autonomous DB가 구현한 자동화는 하드웨어 인프라 단의 자동화, 데이터베이스 소프트웨어 단의 자동화, 그리고 데이터 센터 운영 단의 자동화로 구성되어 있으며, 모든 레이어에 걸쳐 최신의 머신 러닝 기법이 적용되었습니다. 
- 오라클 Autonomous DB는 급격하고 이질적인 도약이 아니라, 오라클 9i 출시 이래 20 여년에 걸쳐 일관된 목표를 가지고 지속적으로 발전되어 온 오라클 자동화 기술의 정점에 서 있는 데이터베이스 서비스입니다.
- 이와 같은 자율 운영의 제 1 목표는 IT 관리자 또는 데이터베이스 관리자 (DBA)에 의해 전통적으로 수행되어 왔던 일상적인 관리 작업에 드는 노력을 최대한 제거하여 기업의 역량을 **운영이 아닌 혁신**에 집중할 수 있도록 돕는 것입니다.

## Hands-On

#### 19c ADG DML Redirect 

- [19c ADG DML Redirec](https://github.com/oracle19c-cookbook/Availability-Scalability/blob/master/AciveDataGuard/19c_ADG_DML_Redirect.pdf)


## 참고 자료

- 공식 매뉴얼
    - [Performing DML Operations on Active Data Guard Standby Databases ](https://docs.oracle.com/en/database/oracle/oracle-database/19/sbydb/managing-oracle-data-guard-physical-standby-databases.html#GUID-8AAD002C-ED06-4349-8BB5-EC8DB30B2628)
- White Papaper 
    - [Oracle Autonomous Database Technical Overview](https://www.oracle.com/a/ocom/docs/database/oracle-autonomous-database-technical-overview.pdf)
    - [Oracle Autonomous Database Strategy](https://www.oracle.com/a/ocom/docs/database/oracle-autonomous-database-strategy-wp.pdf)
    - [Oracle Autonomous Database: The Industry's First Self Securing Database](https://www.oracle.com/a/ocom/docs/database/autonomous-database-self-securing-wp.pdf)
    - [Oracle Autonomous Database: The Industry's First Self Repairing  Database](http://www.oracle.com/us/products/database/autonomous-database-self-repairing-5116047.pdf)
- 기타
    - Cloud Essentials: [Run Critical Databases in the Cloud](http://www.oracle.com/us/solutions/cloud-essentials-data-mgmt-3901529.pdf)
    - Infographic: [Discover new roads with an autonomous database](https://www.oracle.com/a/ocom/docs/cloud/do-more-with-oci-adb-Infographic.pdf)
