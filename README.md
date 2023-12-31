# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유
[vite](https://ko.vitejs.dev/guide/)
웹 애플리케이션을 더 빠르게 개발하고 더 빠르게 빌드하는 것을 목표로 합니다.

## Vite의 주요 특징
1. 빠른 개발 서버: Vite는 개발 서버를 통해 코드를 실시간으로 빠르게 빌드하고 제공합니다. 이로써 개발자는 빠른 리로드 및 개발 환경에서의 빠른 피드백을 얻을 수 있습니다.
2. 빠른 빌드: 프로덕션 빌드 시 Vite는 최적화된 빌드 프로세스를 사용하여 작은 번들 크기와 빠른 로딩 속도를 제공합니다.
3. ES 모듈 기반: Vite는 기본적으로 ES 모듈을 사용하며, 개발 시에 각 모듈을 개별적으로 불러오므로 불필요한 코드를 로드하지 않아 최적화가 용이합니다.
4. Vue.js 지원: Vite는 Vue.js를 위한 개발 환경을 최적화하였으며, Vue.js 프로젝트에서 사용하기에 이상적입니다.
5. 다양한 플러그인 및 확장성: Vite는 다양한 플러그인을 지원하며, 사용자 정의 설정을 통해 프로젝트에 맞는 개발 환경을 구축할 수 있습니다.

## 설치
`npm run dev` 실행하기

## 구현 기능
- 구글 폰트 적용


## 트러블 슈팅
<details>
<summary>git 업로드 버그</summary>
권한으로 인한 업로드 버그 현상이 생김 > 해결
git the requested URL returend error : 403 해결방법
git remote set-url origin https://github.com/hee031812/vite-project01.git

1. 인증하기
github-username -> (내가 githb에서 사용하는 이름)
github-repository-name -> git reposit 이름을 입력 (큰따옴표 제거)
***제일 처음에 git remote add origin git_reposit_주소.git 을 통해 origin 명칭을 만들었지만 해당 주소에 대한 권한이 없어서 푸쉬를 할 때 에러가 난것임.

2. 소스코드 푸쉬하기
터미널에서 git push -u origin master 를 입력
깃헙 패스워드 입력을 하라는 창이 나오고 입력을 하시면 본인의 깃주소에소스코드가 올라감.
git push만 하면 기존의 세팅한 주소로 바로 푸쉬가 됨. 
변경을 원하면 -> git remote "set-url" "any_name" "git_reposit_주소"를 사용하면된다.1

</details>