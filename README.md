## Project Name

차종별 고속도로 교통량 분석을 통한 안전한 화물차 운행을 위한 고속도로 개선방안 도출

## Purpose

국토교통 공공데이터 활용,분석 아이디어 공모전 참여

## Description

한국 도로 공사가 발표한 자료에 따르면, 졸음-주시태만 비율을 차종별로 따지면 화물차가 57.9%로 절반을 훌쩍 넘는다고 발표하였다. 

그에 따른 정책으로 화물차 전용 휴게소를 설치하였지만 아직 전국적으로 50여개 밖에 설치하지 않았다. 

그리하여 우리 조는 공공데이터 및 KOSIS 자료를 통해 차종별 고속도로 통행량과 사고 비율을 분석하고 사고다발구간을 직접 선정하여 최적의 화물차 휴게소 입지를 제안하고자 한다.


## Stacks
R, python

Notion

## Period

4/26 ~ 5/20

## Role

Notion에서 자세히 작성할 예정

https://www.notion.so/d5b911915e524dc488ebfa8ba805f627?v=e690ed0b3ad243a6a62d5ac05457f80c

## Contact

mesh153@naver.com

## Related Data

공모전 URL

[https://bigdata-transportation.kr/pageant/dashboard/CMPE_000000000020004](https://bigdata-transportation.kr/pageant/dashboard/CMPE_000000000020004)

국토교통부 데이터 통합채널

[http://data.molit.go.kr/](http://data.molit.go.kr/)


국가교통 데이터 오픈마켓

http://bigdata-transportation.kr/


교통사고 분석 시스템

http://taas.koroad.or.kr/](http://taas.koroad.or.kr/

국가 교통 DB

https://www.ktdb.go.kr/www/index.do

교통량 정보 제공 시스템 (구간별 고속도로 통행량 정보)

http://www.road.re.kr/itms/itms_01.asp?pageNum=3&subNum=2

국토교통부_자동차종합정보 api 서비스

[https://www.data.go.kr/data/15071233/openapi.do](https://www.data.go.kr/data/15071233/openapi.do)

국가교통사고분석 시스템

[http://taas.koroad.or.kr/](http://taas.koroad.or.kr/)

## Schedule

4/26 : 아이디어 회의

4/28 : 아이디어 회의

5/04 : 프로젝트 계획서 및 PPT 제작, 공모전 주제 선정

5/05 : ITS 국가교통정보센터 인증키 신청. 개인 제한량 문제로 해당 기관에 제한량을 늘려달라고 요청한 상태. 국가교통정보센터측에서 이메일로 해당 데이터를 보내준다고 연락온 상태

5/07 : 일일 회의

5/09 : 일일 회의 및 각자 역할 수행, 본인은 화물차 사고 현황 및 졸음 운전 사고 데이터 수집 및 시각화 예정, 지도 시각화 코드 준비 

5/10 : Naver geocoding, Google geocoding api를 활용해서 고속도로 각 지점별 위도, 경도 추출. 고속도로 사고 데이터 임시 데이터 확보

5/11 : 교통사고 데이터, 고속도로 통행량 데이터를 통한 시각화, 고속도로 구간별 시각화

5/12 : 고속도로 구간별 교통량 시각화 및 좌표 값 오류 수정

5/14 : 고속도로 구간별 휴게소 카운트 및 KMeans를 활용해서 휴게소 입지 선정을 위한 코드 Check

5/15 : GMM, DBSCAN 등등 타 군집화 알고리즘 구현

5/16 : 고속도로 구간별 사고 건수 체크 및 고속도로 입지 선정을 위한 Kmeans 최적화

5/17 : 시각화 자료 마무리 및 연구 보고서 작성 

5/18 : 보완할 부분 추가 및 마무리 작업

5/19 : 발표
