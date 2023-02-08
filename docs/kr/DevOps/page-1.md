# Jenkins

CI/CD 솔루션 중 하나인 Jenkins 에 대해 다룹니다.

## Pipeline

Pipeline 에 대한 전체적인 설명

### Declarative Pipeline

주로 설명하게 될 Declarative Pipeline 에 대한 설명
사용하는 이유: Scripted Pipeline 과 비교하여 보면, 가장 최신의 기술이고 또 Scripted Pipeline 은 작성하는 사람들이 Jenkins 의 기능을 사용하는 것이 아니라(플러그인 등) 그냥 스크립트로 짜서 사용하는 상황이 자주 나오다 보니, 비효율적이라서 권장되지 않음

구조:
Pipeline -> 에이전트 설정 부분 -> stages -> post step 순으로 이루어져 있으며, 병렬 수행 등 다양한 사용성을 가진다.


### Scripted Pipeline

Scripted Pipeline 에 대한 설명 + 어떤 식으로 사용하게 되는지 등