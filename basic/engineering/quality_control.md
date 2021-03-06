## 품질

* 기능적 요구사항 :

* 기능품질
  * 기능적합성
    * 정확성
    * 완전성
    * 적절성
    * 사용성

* 비기능기능품질
  * 효율성
  * 보수성
  * 신뢰성
  * 견뢰성(견고함)

### Technical Debt (기술적 부채負債)

tech debt, code debt

개발팀이 기능의 빠른 처리나 프로젝트에서 나중에 리팩토링 하기 위해 취한 행동의 결과물을 말한다.
즉, 완벽한 코드보다 빠른 전달을 우선시한 결과물을 뜻한다.

개발 단계에서 제대로 개발을 해놓지 않게 되면 그게 빚이 되고, 나중에 이자가 불어서 더 많은 일을 해야 한다는 것이다.

#### Technical Debt가 생기는 원인

* 비즈니스 조직으로부터의 무리한 압박 : 릴리스에 맞추기 위해 무리하게 코스트로 진행한 경우, 소프트웨어 품질에 문제가 생기고, 결국 나중에 이 부분을 다시 보강해야 한다.

* 부정확한 요구 사항이나 잦은 변경 : 요구사항이 정확하게 정의되지 않으면, 기능이 제대로 개발되지 않고, 후반에 집중되는 경향이 있고, 심각한 품질 문제로 연결된다.

* 잘못된 의사 결정 프로세스 : 비지니스 쪽에서 일정 변경이나 요구 사항 변경에 대한 영향을 인지하지 못하고,일정이나 비용 변경하면, 문제가 발생한다.

* 부족한 협업 : 팀간의 협업 부족으로 정보 공유 잘 안됨

* 부족한 테스팅 : 테스팅의 부족으로 인해 소프트웨어 품질이 저하

* 부족한 문서화 : 문서화 부족으로 향후 참고할 자료 적음

  ...

### 복잡도

#### 인지적 복잡도(Cognitive Complexity)

#### 순환 복자도(Cyclomatic Complexity)

### CK Metrics (Chidamber & Kemerer Metrics)

A Metrics Suite for Object Oriented Design

프로젝트 지향언어에 걸쳐 복잡도 / 

### WMC (Weighted Methods per Class)

### DTT (Depth In Inheritance)

값이 커질수록

### CBO (Coupling Between Objects)

의존하는 클래스 수

결합도(영향을 받고 있는 범위)의 크기(보존성 & 재이용성의 저하)를 나타냄

(값이 클 수록 클래스가 임무를 보유하고있을 가능성 있음(리팩터링 필요성)) 

### 응집도 (Cohesion)과 결합도 (Coupling)

`High Cohesion`, `Low Coupling`

설계하는 것에 정답은 없겠지만, 일반적으로 좋은 설계란

### OO Metrics (Object-Oriented Metrics)

의존하는 클래스 수

결합도(영향을 받고 있는 범위)의 크기(보존성 & 재이용성의 저하)를 나타냄

### 







