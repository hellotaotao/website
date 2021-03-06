---
title: "도구 설치"
description: 컴퓨터에서 쿠버네티스 도구를 설정한다.
weight: 10
no_list: true
---

## kubectl

쿠버네티스 커맨드 라인 도구인 `kubectl` 사용하면 쿠버네티스 클러스터에 대해 명령을
실행할 수 있다. `kubectl` 을 사용하여 애플리케이션을 배포하고, 클러스터 리소스를 검사 및
관리하고, 로그를 볼 수 있다.

클러스터에 접근하기 위해 `kubectl` 을 다운로드 및 설치하고 설정하는 방법에 대한 정보는
[`kubectl` 설치 및 설정](/ko/docs/tasks/tools/install-kubectl/)을
참고한다.

<a class="btn btn-primary" href="/ko/docs/tasks/tools/install-kubectl/" role="button" aria-label="kubectl 설치 및 설정 가이드 보기">kubectl 설치 및 설정 가이드 보기</a>

[`kubectl` 레퍼런스 문서](/ko/docs/reference/kubectl/)를 읽어볼 수도 있다.

## minikube

[`minikube`](https://minikube.sigs.k8s.io/)는 쿠버네티스를 로컬에서 실행할 수 있는
도구이다. `minikube` 는 개인용 컴퓨터(윈도우, macOS 및 리눅스 PC 포함)에서
단일 노드 쿠버네티스 클러스터를 실행하여 쿠버네티스를 사용해보거나 일상적인 개발 작업을
수행할 수 있다.

도구 설치에 중점을 두고 있다면 공식 사이트에서의
[시작하기!](https://minikube.sigs.k8s.io/docs/start/)
가이드를 따라 해볼 수 있다.

<a class="btn btn-primary" href="https://minikube.sigs.k8s.io/docs/start/" role="button" aria-label="minikube 시작하기! 가이드 보기">minikube 시작하기! 가이드 보기</a>

`minikube` 가 작동하면, 이를 사용하여
[샘플 애플리케이션을 실행](/ko/docs/tutorials/hello-minikube/)해볼 수 있다.

## kind

`minikube` 와 마찬가지로, [kind](https://kind.sigs.k8s.io/docs/)를 사용하면 로컬 컴퓨터에서
쿠버네티스를 실행할 수 있다. `minikube` 와 달리, `kind` 는 단일 컨테이너 런타임에서만 작동한다.
`kind` 는 [도커](https://docs.docker.com/get-docker/)를 설치하고
구성해야 한다.

[퀵 스타트](https://kind.sigs.k8s.io/docs/user/quick-start/)는 `kind` 를 시작하고 실행하기 위해
수행해야 하는 작업을 보여준다.

<a class="btn btn-primary" href="https://kind.sigs.k8s.io/docs/user/quick-start/" role="button" aria-label="kind 시작하기 가이드 보기">kind 시작하기 가이드 보기</a>
