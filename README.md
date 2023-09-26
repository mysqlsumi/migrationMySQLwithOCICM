# MigrationMySQLwithOCICM
Migration any MySQL to MDS using OCICM tool

## 0. Pre- Requisite (사전작업)
### 1) Create an OCI Account (OCI 무료 계정 생성)
[How to create OCI Free trial](https://apexapps.oracle.com/pls/apex/r/dbpm/livelabs/run-workshop?p210_wid=3157)


### 2) Create a VCN for Network (네트워크를 위한 VCN 생성)
[How to create a VCN](http://taewan.kim/oci_docs/10_quickstart/vcn/simple_vcn/)



## 1. Migration MySQL on other cloud vendors or On-Prem to MDS OCI
### - Select MySQL DbaaS/On-Premiss MySQL Community Server to OCI MDS menu (아래 화면의 두번째 메뉴선택)
<img width="821" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/84733143-8a70-4eec-92a5-db95afcefe21">


### - Fill in the target MDS information which will be created by OCICM (생성할 MDS 정보 입력)
<img width="776" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/60cf9c57-71b6-472f-bf46-00848e1f941e">


### - Select Availability Domain(AD 선택)
<img width="776" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/e5512da7-b686-494d-aaf1-10dd887daa3d">


### - Select Fault Doamin(FD 선택)
<img width="776" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/33c05d21-e670-45cd-81e0-80be1e940a4d">


### - Select the target VCN(VCN 선택)
<img width="842" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/d2d17dfc-fb87-4bcb-998e-bf213663dd72">


### - Select the target subnet(서브넷 선택)
<img width="942" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/ff4666fd-cd83-48f2-a09a-3e57dd95fb13">


### - Select the MDS Shape(MDS shape 선택)
<img width="769" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/35a598a6-69d4-4c78-9898-a8e847b0d34e">


### -  Select Configuration for the MDS Shape(MDS shape 에 대한 Configuration 선택)
<img width="934" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/8b99756a-f9bd-4cce-a21f-3f67bedbfe11">


### - Fill in the source DB information (소스 DB 정보 입력)
<img width="781" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/de73042a-5952-439f-bede-06cb408cc96e">


* Select a schema on the source DB (소스 DB 에서 전환할 스키마 선택)
<img width="781" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/086ec24c-0dbd-4f25-9285-02c1eff243a0">


* Select the backup parameters(백업에 필요한 파라미터 선택 - default 권장)
<img width="1042" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/86b91273-30bb-490d-91b6-c95cd1277768">


* Confirm the all settings (설정한 값 모두 확인)
<img width="753" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/93ab3ecb-fe25-4f83-af49-cd59005424eb">


* Select the *Task Manager: Manage tasks and launch Migration* menu (메뉴에서 Task Manager: Manage tasks and launch Migration 선택, 이때 실제 수행됨)
<img width="776" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/cf73aa87-0d16-471c-a894-6ad52ef7abf6">


* Select the *Launch : Launch a migration from tasks* (Launch : Launch a migration from tasks 메뉴 선택 후 실행)
<img width="776" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/0522c6e3-bfa1-4d15-a676-7ceec6aaacd0">


* Select the task configuration(수행할 task 설정을 선택 후 실행)
<img width="952" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/a83b1283-290c-4e30-91b8-432cb141f83d">


* Execute the task (실제 수행)
<img width="821" alt="image" src="https://github.com/mysqlsumi/migrationMySQLwithOCICM/assets/31054795/3af0f73e-4937-46ca-bdd7-0a8b1bd51611">


















