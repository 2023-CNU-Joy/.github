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

<p align="center"><img width="592" src="https://github.com/Dobbies-Escape-Diary/2023-CNU-SW-AI-Project-Fair/blob/main/figure/project.png"></p>



<!-- 1. 문제를 저장하는 DB: 출제자가 자신의 서버에서 작성한 문제가 저장되고 권한에 따라 다른 출제자에게 공유 가능
2. 출제자[서버]: 출제자가 원할 때 서버를 작동시켜 시험 응시자들을 수용하고, 응시 결과 수집 가능. 서버가 상시 동작하지 않아도 되므로 비용 절감 효과. 출제자 Interface 제공해 문제를 작성하고 공유 가능
3. 응시자에게 제공되는 VSCode Extension. 
  - 출제자[서버]로부터 문제를 수령하여 문제를 확인한다.
  - VSCode의 'Side bar'에서 각 문제의 예제 입출력을 확인한다.
  - 문제를 응시자 환경에서 Compile 하고 서버로부터 전송받은 테스트케이스에 적용하여 정확도를 검증한다.
  - 문제 풀기 종료 후, 결과를 출제자[서버]로 전송한다. -->

</br>

## 개발 환경

<p align="center"><img width="592" src="https://github.com/Dobbies-Escape-Diary/2023-CNU-SW-AI-Project-Fair/blob/main/figure/system.png"></p>

</br>

## 

- [2023 CNU SW/AI Project Fair](https://github.com/Dobbies-Escape-Diary/2023-CNU-SW-AI-Project-Fair)
