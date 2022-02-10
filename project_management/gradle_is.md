## Build Tool

### What is Build Tool?

`빌드도구`란 `빌드 자동화를 시켜주는 실행가능한 프로그램을 만들어주는 프로그램`을 말한다.

> 빌드 자동화(Build Automation)
>
> Build Automation is the process of automating the creation of a software build and the associated process including: compiling computer source code into binary code, packaging binary code, and running automated tests.

* 빌드 도구의 등장 배경
	* 빠른 기간 동안에 계속해서 늘어나는 라이브러리의 추가
	* 프로젝트를 진행하며 라이브러리 버전을 동기화 하기 어려움


* 빌드 도구의 기능

	라이브러리 의존성을 잡아주고, 컴파일, 테스트, 실행파일 생성을 손쉽게 할 수 있도록 기능 제공

## What is Gradle

빌드 도구, 빌드 시스템, 빌드 툴

ant, maven과 같은 빌드

* 특징

	* 그루비 (Groovy)기반
	* Java와 유사한 문법 구조
	* android 개발용 공식 빌드 도구
	* spring boot에서 빌드 도구로 사용
	* maven, ant등으로 구성되 프로젝트의 gradle로의 변경 기능 제공
	* C, C++, groovy등의 다양한 언어에 대해서도 빌드가 가능하도록 기능을 지원
	* 오픈소스 기반
	* DSL(Domain Specific Language) 제공

		>  `DSL`(Domain Specific Language)이란?
		>
		> `특정 영역을 타겟하고 있는 언어`를 말한다.
		>
		> 예를 들어 `SQL`의 경우, DB의 데이터를 참조하기 위해 날리는 query는 말 그대로 DB에 데이터를 참조하기 위한 목적으로만 사용되며, SLQ로 웹 애플리케이션 서버를 만드는 것은 불가능하다.
		>
		> 반면, JAVA는 SQL을 만들어 낼 수도 있고(사실상 `SQL은 특정한 문법을 가진 문자열`이기 때문) 웹 애플리케이션 서버를 만들 수도 있고, 그 외 원하는 모든 것을 만들어 낼 수 있다.
		>
		> 이렇게 SQL처럼 어떤 목적이 있고, `그 목적만 달성할 수 있는 언어`를 DSL이라고 한다.

DSL을 사용함에 있어서 gradle에서는 크게 4가지 상태로 기능을 나눠서 분류하고 있다.

- 비공개 상태(Internal) : DSL이나 API로 제공 및 공개하고 있지 않은 상태
- 실험상태(Incubating) : 기능이 추가는 돼 있지만, 기능 개선·추가될 여지가 있는 상태
- 공개 상태(Public) : 기능이 검증돼 활용할 수 있는 상태
- 폐지 상태 (Deprecated) : 새로운 기능이 추가됨으로 인해 불필요해졌거나, 없어질 예정인 상태

## Gradle feature

기존의 Ant, Maven의 장점들을 모아 만들어진 JVM 기반의 빌드 도구. Java 혹은 Groovy를 이용해 logic을 개발자의 의도에 따라 설계할 수 있다.

* 오픈소스 기반의 build 자동화 시스템으로 Groovy기반의 DSL로 작성
* `Multi 프로젝트 빌드`를 지원하기 위해 설계됨
* declarative(선언적)
* 설정 주입 방식(Configuration Injection)
* Apache Ivy에 기반한 강력한 의존성 관리
* 원격 저장소나, pom, ivy `파일 없이 연결되는 의존성 관리` 지원
* 빌드를 설명하는 풍부한 도메인 모델
* Build-by-convention을 바탕으로 함
	* `스크립트 길이`와 `가독성` 면에서 매우 우수
* Gradle이 Maven 보다 `빌드 속도`가 최대 100배 빠름









