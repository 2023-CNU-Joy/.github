# Judge On You

## Group Member

<div align="center">
  
|[Eustace](https://github.com/dlwnsrb0829)|[Hojeong Eom](https://github.com/DobiIsFree)|[heejung Kim](https://github.com/hj-k66)
|:---:|:---:|:---:|
|🐻|🦊|🐰|
|<img src="https://avatars.githubusercontent.com/u/39390618?v=4" width="105">|<img src="https://avatars.githubusercontent.com/u/52994616?v=4" width="105">|<img src="https://avatars.githubusercontent.com/u/68041758?v=4" width="105">|

</div>

</br>


## 💻 Summary
- 클라이언트 중심 코딩테스트 플랫폼

기존 **중앙처리 방식**의 코딩테스트 플랫폼에서 발생할 수 있는 문제점을 예방하기 위해 **클라이언트 중심 방식**으로 변경하자!

</br>

## 추진 배경

기존 플랫폼의 경우, 코딩테스트 응시자들은 자신이 작성한 코드를 검증하기 위해 **Judge Engine이 탑재된 서버**로 결과 전송.

서버는 응시자 한명을 처리 후, 다음 응시자의 코드를 처리하는 방식으로 동작한다. 

서버는 빠른 처리를 위해 높은 성능이 요구되고, 이 과정에서 많은 비용이 소모된다.

</br>

## 목표 및 주요 기능

> 코딩 테스트 응시자의 환경에서 코드를 검증하고 결과만 서버로 전송하는 방식으로 전환해, 서버의 부담을 줄이자

- 문제 출제자
  - 출제자 Interface에서 문제 작성
  - 문제에 해당하는 TestCase 작성
  - 문제가 저장된 DB에서 문제를 가져와 시험 출제
  - 출제를 마치면 응시자를 위한 참여 코드 생성
 
- 시험 응시자
  - 문제를 받고 확인
  - 문제를 풀고 정답 코드 작성, 자신의 환경에서 정확도 검증
  - 모든 코드를 작성하고 결과를 출제자에게 전송

</br>

## 프로젝트 구조

<img width="477" alt="스크린샷 2023-05-31 오후 3 29 19" src="https://github.com/DobiIsFree/Dobby-Socks/assets/52994616/78b7a1b3-a73e-4a4c-8173-c91b9fc6f476">

</br>

## 개발 환경

<img width="592" alt="스크린샷 2023-05-31 오후 3 17 11" src="https://github.com/DobiIsFree/Dobby-Socks/assets/52994616/56106fa7-07a8-433b-bad0-fb980edaba29">

</br>

## 활용 방안 및 기대 효과

기존 플랫폼은 출제자 입장에서 플랫폼을 구축하기 복잡한 반면, **JOY**는 간편한 구축 환경 제공한다.

코드 컴파일을 자신의 PC에서 진행하여 사용자의 악의적인 코드를 사전에 차단할 수 있고

주최측의 다양한 프로그래밍 언어 제공을 위한 비용이나 대규모의 처리 요청에 드는 비용 절감할 수 있다는 장점일 지닌다.

코딩테스트 응시자 입장에서 기존 플랫폼은 별도의 IDE에서 작성 후 copy&paste 하는 번거로움이 있었다면

**JOY** 는 VSCode Extension 제공되기 때문에 간편하게 사용할 수 있다. 

또한 코딩테스트 응시자들이 자주 사용하는 IDE로 심리적 안정감을 제공한다.

현재 충남대에서 사용하는 'CCOJ'를 대체할 플랫폼으로 활용할 계획이다.

</br>

## 발표 자료


## Demo
