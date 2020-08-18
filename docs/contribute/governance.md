---
template: overrides/main.html
---

# 오픈소스 프로젝트 거버넌스 구조

오픈소스 프로젝트는 어떻게 관리 될까요? 서로 모르는 다수의 사람들이 어떻게 코드를 함께 작성하며 수많은 사람들이 사용하는 안정적인 제품을 만들어 낼 수 있을까요? 우수한 오픈소스 프로젝트는 명확한 프로젝트 거버넌스 구조를 가지고 있습니다.

## 멤버 구조

오픈소스 프로젝트는 어떻게 관리 될까요? 서로 모르는 다수의 사람들이 어떻게 코드를 함께 작성하며 수많은 사람들이 사용하는 안정적인 제품을 만들어 낼 수 있을까요? 우수한 오픈소스 프로젝트는 명확한 프로젝트 거버넌스 구조를 가지고 있습니다.

### :material-checkbox-marked-circle: Leader

리더는 의사 결정이 필요할 때 최종 결정을 담당하는 사람입니다. 

예를 들어, Linus Torvalds는 Linux Kernel의 원저작자로서 진행사항에 대한 모든 것에 대해 최종 결정권을 가지고 있습니다. 

Node.js 프로젝트와 같은 경우는 Core Technical Committee가 리더의 역할을 수행합니다.


### :material-checkbox-marked-circle: Maintainer

Maintainer는 Leader로부터 특정 영역을 위임받아서 관리합니다. 


### :material-checkbox-marked-circle: Committer

Committer는 Maintainer의 승인을 받지 않고도 프로젝트의 일부에 직접 커밋할 수 있을 정도로 신뢰할 수 있고 책임감이 있는 사람들입니다.

### :material-checkbox-marked-circle: Contributoer

기여자 코드, 문서화 등의 방법으로 오픈소스 프로젝트에 기여합니다. 이러한 기여는 일반적으로 숙련된 Committer 및 Maintainer에 의해 리뷰 과정을 거치게 됩니다.

### :material-checkbox-marked-circle: User

User는 오픈소스 프로젝트의 성장과 발전에 가장 중요한 그룹입니다. 

User 는 프로젝트에 목적을 부여하고, 기능, 버그 리포트 등의 방법으로 피드백을 제공함으로써 프로젝트를 발전시키는 데 도움을 줄 수 있습니다.


## 문서 구조

또한, 다음과 같이 몇가지 공통적으로 사용되는 문서가 있으며, 대개 저장소의 최상위 레벨에 위치합니다.

### :material-checkbox-marked-circle-outline: README

README는 새로운 커뮤니티 멤버를 위한 설명서입니다. 프로젝트가 유용한 이유와 시작 방법에 대해 설명합니다.


### :material-checkbox-marked-circle-outline: LICENSE

모든 오픈소스 프로젝트는 오픈소스 라이선스가 있어야 합니다. 라이선스가 없다면 오픈소스가 아닙니다. 

오픈소스 라이선스를 선택하는 방법은 다음 페이지를 참고하세요. : [https://choosealicense.com/](https://choosealicense.com/)

### :material-checkbox-marked-circle-outline: CONTRIBUTING

README는 프로젝트를 사용하는 사람들에게 도움이 되는 반면, CONTRIBUTING은 프로젝트에 기여하는 사람들을 위한 문서입니다. 어떤 유형의 기여가 필요한지와 기여하는 방법에 대해 설명합니다.

### :material-checkbox-marked-circle-outline: CODE_OF_CONDUCT

커뮤니티가 건강하게 유지되기 위한 참가자의 행동과 관련된 기본 규칙을 설명합니다.


### :material-checkbox-marked-circle-outline: 기타 문서

(규모가 큰 프로젝트의 경우) 튜터리얼, 거버넌스 정책과 같은 문서도 있을 수 있습니다.

