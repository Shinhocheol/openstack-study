# 제1회 스터디

* 진행 일시 : 2017년 4월 5일 오후 7시 30분 ~ 10시
* 장소 : 강남 토즈타워점

## 스터디 진행 방법
* 강의식은 지양
* 각 장을 진행하다가 자신이 잘 알고 있는 부분이 나오면 적극적으로 참여하여 내용을 공유
* 각자의 경험을 최대한 공유하는 스터디를 지향

## 스터디 요약
현재 구축된 인프라로는 증가하는 부하를 감당할 수 없다면? 인프라를 확장해야한다.

* Scale Out
  * 같은 기능을 하는 서버를 여러개 두는 방법. 수평적 확장
* Scale Up
  * 서버 자체의 성능을 높인다. (예: 메모리 증설)

플랫폼 : CPU + OS + 운영환경

* 프로세스
 * 독립된 메모리 공간을 할당받아 실행되는 프로그램
* 쓰레드
 *  프로세스의 메모리를 공유해서 실행하는 Task

프로그램을 메모리에 올리는 이유
* symbol을 활용하기 위함
* HDD에서 파일을 읽는 파일시스템은 소프트웨어적인 처리를 한다.
* CPU는 기계 그자체이기 떄문에 소프트웨어 적인 내용을 처리할 수 없다
* 메모리에 올라가면 주소와 심볼만 남는다.

운영체제의 핵심 역할은 시스템 API를 제공해주는 것이다.