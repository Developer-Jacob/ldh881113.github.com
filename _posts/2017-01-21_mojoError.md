---
layout: post
title: "[트러블 슈팅] org apache maven plugin war warmojo 에러"
description: "메이븐 초기 설치 시 pom.xml에서 발생하는 org apache maven plugin war warmojo 에러"
date: 2017-01-21
tags: [maven, 메이븐, 루키교육, 개발, 트러블 슈팅]
comments: true
share: true
---

### 트러블 슈팅

* 문제 상황: 
<br>
메이븐 초기 설치 시 pom.xml의 상단에 다음과 같은 에러가 발생한다. 
<br>
“org apache maven plugin war warmojo” 이외의 추가적인 에러 메시지가 보이지 않는다. 
<br>
Dependency 추가, maven install, 프로젝트 clean, 업데이트로는 문제가 해결 되지 않았다. 

* 원인: 정확한 원인은 찾지 못했으나 maven 설치나 dependency의 문제로 판단된다.

* 해결 방안: Maven repository 강제 삭제 후 재설치
