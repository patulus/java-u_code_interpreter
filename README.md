# 허프만 코딩

## 일정
| 일시 | 내용 |
|-----|------|
| '24.11.04, 05. | 레벨3 문제 소개 |
| '24.11.11, 12.| 문제분석서 발표 |
| '24.11.18, 19.| 설계서 발표 |
| '24.12.02, 03, 09, 10. | 결과 보고서 발표 |

## 개요
허프만 코딩(Huffman coding)은 자료 압축의 가장 오래되고 기초적인 방법 중의 하나이며 최소 중복 코딩(minimum redundancy coding)에 기반한 알고리즘을 사용한다.
최소 중복 코딩은 문자들이 자료 집합에서 얼마나 자주 발생하는지를 안다면 발생되는 문자들의 비율에 따라 자주 반복되는 문자들을 더 적은 비트로 부호화 하는 방법이다.
일반적인 경우 한 문자를 표현하기 위해 한 개의 바이트(ASCII 코드)를 사용하나 허프만 코드는 문자 발생 비율에 따라 다른 크기의 비트로 표현한다.

## 기본 문제
임의의 텍스트 파일이 주어지면 허프만 코딩 방법을 이용하여 자료를 압축하며, 압축된 파일이 주어지면 이를 해제하는 프로그램을 작성한다.
다수의 텍스트 파일에서 실험을 수행하여 각각의 압축률과 평균적인 압축률을 계산해 본다.

## 입출력
□ 압축의 경우
   - 입력 : 압축되지 않은 임의의 텍스트 파일
   - 출력 : 허프만 코드로 압축된 파일

□ 압축 해제의 경우
   - 입력 : 허프만 코드로 압축된 파일
   - 출력 : 압축 해제된 일반 텍스트 파일

## 제한요소 및 요구사항
▪허프만 코드로 압축한 파일은 이진 파일로 저장한다.

▪허프만 코드로 압축한 파일은 허프만 테이블과 허프만 부호화코드를 포함한다.

▪50,000자, 100,000자, 500,000자 이상의 텍스트 파일을 직접 준비한다.

▪여러 가지 텍스트 파일에 대해 압축을 수행하여 파일별 및 평균적인 통계정보(압축률, 문자당 평균 비트 수, 압축 및 복원 시간 등)를 계산한다.

## 확장 문제
① GUI 구현

② ASCII 문자 이외의 문자(한글, 유니코드 등)에 대해서도 동작하도록 한다. (본 기능의 구현은 쉽지 않을 것으로 판단됨 - 문제 분석 시 구현 가능성에 대해 검토 후 구현 여부 결정)

## 채점 기준
|범위|구현 기능|배점|비고|
|---|-----|---|----------|
|기본 기능| 테스트용 파일 준비 | 3 | |
| | 메뉴 방식 실행 | 2 | |
| | 압축 및 파일 저장 | 4 | |
| | 비트 단위 저장 | 2 | |
| | 해제 및 파일 저장 | 4 | |
| | 해제 및 화면 출력 | 2 | |
| | GUI 구현 | 3 | |
| 추가 기능 | | | 기본 기능 외의 추가 기능 |
| | | | |
