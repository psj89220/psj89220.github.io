---
date: 2020-11-02 18:46:47
layout: post
title: 코드리스 백엔드(Codeless Backend)
subtitle: DB 연동부터 AuthN&Z 까지
description: 백엔드 언제다해...
category: code
tags:
  - codeless backend
  - postgrest
  - keycloak
author: A
paginate: false
---
대부분은 백엔드는 데이터베이스와 프론트엔드 사이의 중계만을 담당한다. 그런데도 신규 프로젝트가 생길 때마다 단순한 중계를 위 백엔드를 개발하는 데에 골머리를 앓게 된다.

회사 일을 도와주시는 킹갓개발자분의 도움으로 한 기사를 보게 되었는데 흥미로워 나름대로 읽고 정리해봤다.

[원문 - "CodeLess" backend using postgres, postgrest and oauth2 authentication with keycloak](https://www.mathieupassenaud.fr/codeless_backend/)

오늘은 PostgREST, SQL(PostgreSQL), Keycloak을 이용해 사용자 관리 가능한 백엔드를 구축해 볼 것이다.



## 1. PostgreSQL(Database) 설치



## 2. Authentication Server(Keycloak) 설치

## 3. [PostgREST](http://postgrest.org/en/v7.0.0/index.html)(REST API) 설치

백엔드 개발자에게 Database에 대한 부담을 지우기 위한 노력은 예전부터 있어왔다. ORM(Object Relational Mapping) 혹은 ODM(Object Data Mapping)과 같은 기술이 그것인데, ORM 라이브러리를 이용해 SQL 쿼리를 사용하지 않고도 데이터베이스에 CRUD가 가능하도록 하는 기술. 

PostgREST의 경우엔 반대로, SQL만 사용하여 백엔드를 구성할 수 있게 한다.

실행방법은 여러 가지가 있는데 1. binary 파일을 다운받아 실행 2. Docker로 실

## 4. Database 테이블 생성 및 테스트