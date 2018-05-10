# Git Flow

​	![github-flow-repository-structure](http://woowabros.github.io/img/2017-10-30/github-flow_repository_structure.png)

* Upstream Remote Repository : 개발자들이 공유하는 저장소, 최신 소스코드가 저장되어 있는 원격 저장소
* Origin Remote Repository : Upstream Repository를 Fork한 원격 개인 저장소
* Local Repository : 내 컴퓨터에 저장되어 있는 개인 저장소

## 1. 흐름

1. Local Repo에서 작업을 완료한 후 작업 브랜치를 Origin Repo에 push
2. github에서 Origin Repo에 push한 브랜치를 Upstream Repo에 merge하는 Pull Request를 생성하고 코드리뷰를 거친 후 merge
3. 다시 새로운 작업을 할 때 Local Repo에서 Upstream Repo를 pull

## 2. Git-Flow 전략

* 5가지 종류의 브랜치가 존재
* 항상 유지되는 메인 브랜치 : master, develop
* 일정 기간 동안만 유지되는 보조 브랜치 : feature, release, hotfix