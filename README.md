# How-to-write-README.md

# 프로젝트명
> 간략한 프로젝트 소개 문구를 작성합니다.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

한 두 문단으로 프로젝트 소개 글을 작성합니다.

![](../header.png)

## 프로젝트 제목

> 프로젝트 제목은 매우 중요하다. 초보 개발자라면 제목만으로도 어떤 기술을 사용하여 무슨 프로젝트를 만들었는지 상대방이 이해할 수 있게 직관적으로 작성한다.
프로젝트 소개 웹 사이트도 잊지 말고 추가한다. heroku, surge.sh, gh-pages 등 무료 호스팅 서비스가 많으니 이를 적극적으로 활용한다. 특히 gh-pages는 마크다운으로 정적페이지를 만들어주니 꼭 사용해보자.

> 프로젝트에 사용한 기술, 분야, 주제 등 태그도 추가해 프로젝트 메인 페이지를 풍성하게 만든다.

## 프로젝트 내용
> 짧은 소개 문구와 한 문단 분량의 프로젝트 내용을 적는다. 프로젝트의 목적과 동기, 주요 기능이 잘 드러나있어야 한다.

> 직접 개발 환경을 로컬 컴퓨터에 구축하는 사용자는 많지 않다. 무엇보다 사용자에게 프로젝트 실제 데모를 보여주는 것이 중요하다. 배포를 하거나 설치가 필요한 프로그램이라면 반드시 데모를 추가하자. 스크린 캡쳐 프로그램으로 스크린 녹화를 하고 gif 파일로 변환한다. 영상이 필요하면 유투브에 올리고 링크를 건다.

## 설치 방법

OS X & 리눅스:

```sh
npm install my-crazy-module --save
```

윈도우:

```sh
edit autoexec.bat
```
> 실력과 관계없이 누구나 개발 환경을 설치할 수 있어야 한다. 사용자가 설치 과정 중 좌절하지 않게 최대한 자세하고 친절하게 작성한다. 운영 체제 별(OS X/Linux/Windows 등) 설치 방법도 작성한다. 가능한 사용자가 간단한 명령어로 설치를 끝내도록 설치 과정을 간결하게 만드는 것이 좋다.

## 코드 예제, 사용 예제

> 설치 이후 실제 사용 방법 가이드를 작성한다. 코드 예제와 실제 적용 사례를 보여준다.
스크린 샷과 코드 예제를 통해 사용 방법을 자세히 설명합니다.
_더 많은 예제와 사용법은 [Wiki][wiki]를 참고하세요._

## 개발 환경 설정

모든 개발 의존성 설치 방법과 자동 테스트 슈트 실행 방법을 운영체제 별로 작성합니다.

```sh
make install
npm test
```

>잠재적인 컨트리뷰터가 당신의 프로젝트에 기여할 수 있도록 명확한 가이드를 제시한다. 개발 의존성 설치와 자동 테스트 슈트를 실행해 사용자가 개발 환경을 올바르게 설정했는지 확인할 수 있게 한다. 또한 신규 버전 소프트웨어를 빌드하고 릴리스하는 방법도 작성한다.

## 업데이트 내역

* 0.2.1
    * 수정: 문서 업데이트 (모듈 코드 동일)
* 0.2.0
    * 수정: `setDefaultXYZ()` 메서드 제거
    * 추가: `init()` 메서드 추가
* 0.1.1
    * 버그 수정: `baz()` 메서드 호출 시 부팅되지 않는 현상 (@컨트리뷰터 감사합니다!)
* 0.1.0
    * 첫 출시
    * 수정: `foo()` 메서드 네이밍을 `bar()`로 수정
* 0.0.1
    * 작업 진행 중
    
>사용자는 마지막 버전과 비교하여 어떤 변경 사항이 있었는지 확인할 수 있어야 한다. 기능 개선과 수정 내역을 함축적으로 정리하여 로그 변경 히스토리를 관리한다.

## 정보

이름 – [@트위터 주소](https://twitter.com/dbader_org) – 이메일주소@example.com

XYZ 라이센스를 준수하며 ``LICENSE``에서 자세한 정보를 확인할 수 있습니다.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## 기여 방법

1. (<https://github.com/yourname/yourproject/fork>)을 포크합니다.
2. (`git checkout -b feature/fooBar`) 명령어로 새 브랜치를 만드세요.
3. (`git commit -am 'Add some fooBar'`) 명령어로 커밋하세요.
4. (`git push origin feature/fooBar`) 명령어로 브랜치에 푸시하세요. 
5. 풀리퀘스트를 보내주세요.

> 깃허브 리퍼지토리 대부분은 오픈 소스다. 누구나 소스 코드를 다운받아 개발 환경을 구축할 수 있고 개선시킬 수 있다. 당신의 프로젝트에 관심을 가진 누군가 직접 기여할 수 있다. 따라서 개발 프로세스와 기여 방법에 관한 명확한 지침을 제공해야 한다.

## 크레딧 
> 오픈 소스 프로젝트를 사용해 만들었거나, 누군가로부터 큰 도움을 받았거나, 크게 기여한 사람이 있다면 잊지 않고 꼭 언급하자.

## 라이센스
> 라이센스를 명시하고 디렉터리에 LICENSE.txt를 포함시키자.  오픈 소스 라이센스(영문), 오픈소스 SW 라이센스 종합시스템(국문) 라이센스 목록을 확인할 수 있다. 가장 많이 쓰는 라이센스는 MIT 라이센스, Apache 2.0 라이센스, ISC 라이센스, BSD 라이센스다.
<https://www.olis.or.kr/license/licenseGuide.do>

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki

