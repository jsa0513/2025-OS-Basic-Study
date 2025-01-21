# Chap15-08 : 파일 시스템 내부구조_NFS
네트워크 파일 시스템의 구현과 명세

## 


### Stateful vs Stateless
**Stateful**
* 서버가 클라이언트의 상태 보존
* 클라이언트 상태를 가지므로 용량 한계 O
> 로그인 유지
>
> 쿠키 저장
>
> 세션 메모리 유지

**Stateless**
* 서버가 클라이언트의 상태 보존 X
* 요청 -> 응답만 수행
* 대량의 트래픽이 발생해 서버 확장이 필요할 때에도 대처가 용이 Chap15-08 : 파일 시스템 내부구조_NFS
네트워크 파일 시스템의 구현과 명세

## 


### Stateful vs Stateless
**Stateful**
* 서버가 클라이언트의 상태 보존
* 클라이언트 상태를 가지므로 용량 한계 O
> 로그인 유지
>
> 쿠키 저장
>
> 세션 메모리 유지

**Stateless**
* 서버가 클라이언트의 상태 보존 X
* 요청 -> 응답만 수행
* 대량의 트래픽이 발생해 서버 확장이 필요할 때에도 대처가 쉬움

## 참고 자료
[아주 쉽게 이해하는 Stateful / Stateless 차](https://inpa.tistory.com/entry/WEB-%F0%9F%93%9A-Stateful-Stateless-%EC%A0%95%EB%A6%AC)
