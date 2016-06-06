# 1차 면접 발표자료 - 김진영 

[TOC]

## Who am I

- 국내외 이동통신사의 RBT(Ring Back Tone, 통화대기연결음), IVR(Interactive Voice Resposne) VOD/Live 스트리밍등의 응용 부가서비스 및 SMSC(Short Message Service Center),MRF(Media Resource Function) 등의 코어망 서버 개발
- Linux 환경에서 네트워크 및 스토리지 구성 및 시스템 구축, 개발환경 구성 및 Admin 등의 SE 업무 경험
- C/C++, Java(J2EE,Servlet) 개발 경험 (새로운 언어에 큰 제약은 없음)
- Javascript 기반의 Node.js,Angular.js 를 이용하여 웹/모바일 서비스 기획, 개발 및 배포 경험
- 새로운 기술을 스터디하고, 업무에 적용, 공유하는 것을 좋아하고, 서비스에 관심이 많아서 아이디어를 실제로 구현해보려고 하는 편임. 
- 맡은 업무에 대해서 책임감이 강하고, 개인보다는 팀웍을 중요하게 생각함.

## What I did

1. RBT Player
	- 시그널링 프로토콜 처리 ( ISUP,SIP )
	- 가입자 프로파일 DB 서버 연동, business logic 처리
	- MRFP or 스트림서버 제어 ( MSML over SIP )
![RBT](http://www.eluon.com/_image/144)
2. IVR (Interactive Voice Response)

	- VoiceXML Interpreter와 연동, IVR 시나리오 처리
	- MRFP 제어 ( Radisys 상용 제폼)
![IVR](http://i.imgur.com/1ZQH3B9.png?1)
3. MRF
	- G.711, AMR-WB 음성코덱과 H.264 영상 코덱 지원 MRFP(AMP-S)
	- RTCP,RTP/AVPF(Audio Video Profile Feedback) 처리 기능 개발
	- Recording 기능 개발중

4. VoIP 관련 응용 서비스
5. ETC
	- ELK 이용한 Log 분석 모듈
	- 모니터링 모듈
	- 시스템 구축 및 기술 지원

## Plan Call 서비스 소개
Mst login: Tue Jun  7 00:44:50 on ttys002
➜  ~
➜  ~
➜  ~
➜  ~ cd git
➜  git ls
AMP-S                                         cplanner                                      krawler                                       package.json
HelloCpp                                      creating-your-first-desktop-app-with-electron kurento-tutorial-js                           person-demo-angular2-seed
Ionic-Material-master                         css                                           kurento-tutorial-node                         projectwebdev-api
MyDirectory                                   cuteUppyPics                                  loopback-angular-admin                        push-notification-server
MyIonic2Project                               devtest                                       loopback-component-push                       push-tutorial
MyIonicProject                                electron                                      loopback-component-storage                    pythonExam
RTCMultiConnection                            electron-quick-start                          loopback-example-angular                      rabbitmq
SPA-test                                      electronApp                                   loopback-example-mysql                        rabbitmq-example
amps                                          ex1                                           loopback-example-passport                     screencat
angular-material-dashboard                    freeswitch                                    loopback-example-relations                    simple-login
angular-material-starter                      hapiExample                                   loopback-example-two-factor                   slate
callplannerApp                                helloworld-c                                  loopback-getting-started-intermediate         splashscreenApp
callplannerV2_dev                             index.html                                    loopback-material-admin                       test
callplanner_dev                               ion-chapter6                                  loopbackadmin                                 test1
callplanner_github                            ionic-loopback-example                        main.js                                       thtest
chapter5                                      ionic-timeline                                nightmare                                     thtest.c
chapter6                                      ionic-weatherCast-app                         node-mail                                     timeline-ionic
cheerioTest                                   ionicPickContact                              node_modules                                  typescriptExamples
com-realnetworks-ionicApp                     js                                            nylas-nodejs                                  ui-router-test
contentmanager2                               keyChain                                      package                                       utils
➜  git
➜  git
➜  git ls -lrt
total 56
drwxr-xr-x   18 kimjin-young  staff   612  5 11  2015 loopback-example-angular
drwxr-xr-x    6 kimjin-young  staff   204  5 13  2015 ui-router-test
drwxr-xr-x   18 kimjin-young  staff   612  5 21  2015 node-mail
drwxr-xr-x   11 kimjin-young  staff   374  5 27  2015 package
drwxr-xr-x   15 kimjin-young  staff   510  5 29  2015 loopback-example-two-factor
drwxr-xr-x   16 kimjin-young  staff   544  6  1  2015 loopback-example-relations
drwxr-xr-x   16 kimjin-young  staff   544  6 17  2015 loopback-example-mysql
drwxr-xr-x   24 kimjin-young  staff   816  6 29  2015 loopback-component-push
drwxr-xr-x   14 kimjin-young  staff   476  7  7  2015 simple-login
drwxr-xr-x   17 kimjin-young  staff   578  7 13  2015 chapter5
drwxr-xr-x   18 kimjin-young  staff   612  7 14  2015 chapter6
drwxr-xr-x   17 kimjin-young  staff   578  7 15  2015 ionic-weatherCast-app
drwxr-xr-x   14 kimjin-young  staff   476  7 15  2015 ionic-timeline
drwxr-xr-x   15 kimjin-young  staff   510  7 15  2015 splashscreenApp
drwxr-xr-x   16 kimjin-young  staff   544  7 15  2015 com-realnetworks-ionicApp
drwxr-xr-x   16 kimjin-young  staff   544  7 20  2015 ion-chapter6
drwxr-xr-x   14 kimjin-young  staff   476  7 24  2015 timeline-ionic
drwxr-xr-x@  21 kimjin-young  staff   714  7 27  2015 Ionic-Material-master
drwxr-xr-x   18 kimjin-young  staff   612  7 29  2015 ionicPickContact
drwxr-xr-x   18 kimjin-young  staff   612  8  6  2015 ionic-loopback-example
drwxr-xr-x   17 kimjin-young  staff   578  9  8  2015 push-tutorial
drwxr-xr-x   13 kimjin-young  staff   442 11 11  2015 push-notification-server
drwxr-xr-x   19 kimjin-young  staff   646 11 11  2015 callplanner_github
drwxr-xr-x   14 kimjin-young  staff   476 11 18  2015 loopback-example-passport
drwxr-xr-x   19 kimjin-young  staff   646 11 20  2015 callplannerV2_dev
drwxr-xr-x   21 kimjin-young  staff   714 11 25  2015 angular-material-dashboard
drwxr-xr-x   22 kimjin-young  staff   748 11 25  2015 angular-material-starter
drwxr-xr-x   32 kimjin-young  staff  1088 12 11 10:15 loopbackadmin
drwxr-xr-x   31 kimjin-young  staff  1054 12 15 15:38 loopback-material-admin
drwxr-xr-x   51 kimjin-young  staff  1734 12 15 16:22 freeswitch
-rw-rw-r--@   1 kimjin-young  staff   298 12 16 17:01 package.json
-rw-rw-r--@   1 kimjin-young  staff  1258 12 16 17:01 main.js
drwxrwxr-x@   5 kimjin-young  staff   170 12 16 17:01 js
-rw-rw-r--@   1 kimjin-young  staff   574 12 16 17:01 index.html
drwxrwxr-x@   4 kimjin-young  staff   136 12 16 17:01 css
drwxr-xr-x   11 kimjin-young  staff   374 12 21 17:03 cplanner
drwxr-xr-x   12 kimjin-young  staff   408 12 22 09:37 callplanner_dev
drwxr-xr-x   13 kimjin-young  staff   442 12 22 09:49 devtest
drwxr-xr-x   20 kimjin-young  staff   680  1  6 15:46 nylas-nodejs
drwxr-xr-x   20 kimjin-young  staff   680  1  6 17:51 RTCMultiConnection
drwxr-xr-x    3 kimjin-young  staff   102  1 26 15:22 rabbitmq
drwxr-xr-x    9 kimjin-young  staff   306  1 29 09:20 rabbitmq-example
drwxr-xr-x   34 kimjin-young  staff  1156  1 29 13:46 loopback-angular-admin
drwxr--r--   28 kimjin-young  staff   952  2 12 11:24 SPA-test
drwxr-xr-x   23 kimjin-young  staff   782  2 12 13:36 ex1
drwxr-xr-x    2 kimjin-young  staff    68  2 12 13:49 test1
drwxr-xr-x    2 kimjin-young  staff    68  2 12 14:19 electronApp
drwxr-xr-x   16 kimjin-young  staff   544  2 12 16:25 slate

-rw-r--r--    1 kimjin-young  staff  1034  2 15 11:30 thtest.c
-rwxr-xr-x    1 kimjin-young  staff  9100  2 15 11:30 thtest
drwxr-xr-x    7 kimjin-young  staff   238  2 19 09:23 helloworld-c
drwxr-xr-x    3 kimjin-young  staff   102  2 19 09:42 HelloCpp
drwxr-xr-x    4 kimjin-young  staff   136  2 19 09:54 amps
drwxr-xr-x    2 kimjin-young  staff    68  2 19 13:10 cheerioTest
drwxr-xr-x   11 kimjin-young  staff   374  2 19 17:23 krawler
drwxr-xr-x    6 kimjin-young  staff   204  2 24 15:46 utils
drwxr-xr-x    8 kimjin-young  staff   272  2 26 18:18 pythonExam
drwxr-xr-x   18 kimjin-young  staff   612  3 30 11:02 cuteUppyPics
drwxr-xr-x   13 kimjin-young  staff   442  3 30 14:07 MyIonicProject
drwxr-xr-x   16 kimjin-young  staff   544  3 30 14:27 MyIonic2Project
drwxr-xr-x   11 kimjin-young  staff   374  3 31 16:29 MyDirectory
drwxr-xr-x   10 kimjin-young  staff   340  4  5 10:18 AMP-S
drwxr-xr-x   10 kimjin-young  staff   340  4  7 17:18 typescriptExamples
drwxr-xr-x   14 kimjin-young  staff   476  4 18 13:54 kurento-tutorial-node
drwxr-xr-x   16 kimjin-young  staff   544  4 18 14:09 kurento-tutorial-js
drwxr-xr-x    2 kimjin-young  staff    68  4 19 17:19 electron
drwxr-xr-x   11 kimjin-young  staff   374  4 19 17:40 electron-quick-start
drwxr-xr-x    7 kimjin-young  staff   238  4 20 11:34 keyChain
drwxr-xr-x   17 kimjin-young  staff   578  4 21 15:56 test
drwxr-xr-x    5 kimjin-young  staff   170  4 29 10:56 hapiExample
drwx------@   8 kimjin-young  staff   272  5  2 15:33 creating-your-first-desktop-app-with-electron
drwxr-xr-x    5 kimjin-young  staff   170  5  3 14:19 projectwebdev-api
drwxr-xr-x   17 kimjin-young  staff   578  5  4 10:06 person-demo-angular2-seed
drwxr-xr-x   18 kimjin-young  staff   612  5 11 16:06 loopback-getting-started-intermediate
drwxr-xr-x   28 kimjin-young  staff   952  5 13 10:45 screencat
drwxr-xr-x  157 kimjin-young  staff  5338  5 13 17:15 node_modules
drwxr-xr-x    7 kimjin-young  staff   238  5 18 11:07 nightmare
drwxr-xr-x   17 kimjin-young  staff   578  6  2 20:16 loopback-component-storage
drwxr-xr-x   20 kimjin-young  staff   680  6  3 09:21 contentmanager2
drwxr-xr-x   13 kimjin-young  staff   442  6  6 14:04 callplannerApp
# 1차 면접 발표자료 - 김진영

[TOC]

## Who am I

- 국내외 이동통신사의 RBT(Ring Back Tone, 통화대기연결음), IVR(Interactive Voice Resposne) VOD/Live 스트리밍등의 응용 부가서비스 및 SMSC(Short Message Service Center),MRF(Media Resource Function) 등의 코어망 서버 개발
- Linux 환경에서 네트워크 및 스토리지 구성 및 시스템 구축, 개발환경 구성 및 Admin 등의 SE 업무 경험
- C/C++, Java(J2EE,Servlet) 개발 경험 (새로운 언어에 큰 제약은 없음)
- Javascript 기반의 Node.js,Angular.js 를 이용하여 웹/모바일 서비스 기획, 개발 및 배포 경험
- 새로운 기술을 스터디하고, 업무에 적용, 공유하는 것을 좋아하고, 서비스에 관심이 많아서 아이디어를 실제로 구현해보려고 하는 편임.
- 맡은 업무에 대해서 책임감이 강하고, 개인보다는 팀웍을 중요하게 생각함.

## What I did

1. RBT Player
        - 시그널링 프로토콜 처리 ( ISUP,SIP )
        - 가입자 프로파일 DB 서버 연동, business logic 처리
        - MRFP or 스트림서버 제어 ( MSML over SIP )
![RBT](http://www.eluon.com/_image/144)
2. IVR (Interactive Voice Response)

        - VoiceXML Interpreter와 연동, IVR 시나리오 처리
        - MRFP 제어 ( Radisys 상용 제폼)
![IVR](http://i.imgur.com/1ZQH3B9.png?1)
3. MRF
        - G.711, AMR-WB 음성코덱과 H.264 영상 코덱 지원 MRFP(AMP-S)
        - RTCP,RTP/AVPF(Audio Video Profile Feedback) 처리 기능 개발
        - Recording 기능 개발중

4. VoIP 관련 응용 서비스
5. ETC
        - ELK 이용한 Log 분석 모듈
        - 모니터링 모듈
        - 시스템 구축 및 기술 지원

## Plan Call 서비스 소개
MRFP의 컨퍼런스 기능을 이용하여 기존의 컨퍼런스 콜 서비스의 불편한 점을 개선, 웹/모바일에서 아웃룩이나 구글 캘린더에 컨퍼런스 일정을 등>록하면 컨퍼런스 시간에 맞춰 시스템에서 자동으로 컨퍼런스를 생성하여 참석자에게 콜하는 서비스로 일정 공유, 참석자의 상태 참석 여부 확인, 레코딩, 영상 회의 및 화면 공유(추후 지원 예정) 기능을 제공합니다.
"README.md" 95L, 4889CRFP의 컨퍼런스 기능을 이용하여 기존의 컨퍼런스 콜 서비스의 불편한 점을 개선, 웹/모바일에서 아웃룩이나 구글 캘린더에 컨퍼런스 일정을 등록하면 컨퍼런스 시간에 맞춰 시스템에서 자동으로 컨퍼런스를 생성하여 참석자에게 콜하는 서비스로 일정 공유, 참석자의 상태 참석 여부 확인, 레코딩, 영상 회의 및 화면 공유(추후 지원 예정) 기능을 제공합니다.
### Requirement
1.유저는 최초에 App을 설치하고 회원 가입을 합니다.( Sign up )
2.회원 가입이 끝나면 푸시 알림을 위한 AppId를 Push Server에 등록합니다.
3.가입된 아이디와 패스워드 혹은 소셜 계정으로 로그인을 합니다.
4.화면에 유저가 생성한 Plan이나 유저가 멤버로 등록된 Plan 리스트가 표시됩니다.
5.유저가 신규로 플랜을 설정합니다.
6.플랜 생성시, 유저가 녹음한 안내멘트가 있으면 Content Manager 서버에 멘트를 업로드 합니다. 이 때 자동으로 MRFP가 지원하는 포맷으로 컨버팅 됩니다.(3gp convert to wav)
7.콜 플래너는 푸시 서버에게 푸시 메시지를 전송하도록 요청합니다.
8.푸시 서버는 멤버에게 컨퍼런스에 대한 참석 여부를 확인하는 푸시 메시지를 전송합니다.
- 참석 여부를 확인하는 푸시를 받은 Attendee A는 스케쥴된 시간에 전화를 받을 수 있는 멤버입니다. 스케쥴 시간에 MRFP는 이 멤버에게 전화를 겁니다.
- Attendee B는 전화를 받을 수 없는 멤버입니다. 이 멤버에게는 전화를 걸지 않습니다.( 대신에 나중에  컨퍼런스에 조인할 수 있도록 Conference ID 번호를 알려줍니다.  )

9.스케쥴 시간에 콜 플래너는 MRF에게 Call을 요청합니다.MRFC는 컨퍼런스 참석을 확인한 Host A와 Attendee A에게 전화를 겁니다.
10.Attendee B에게는 나중에라도 컨퍼런스에 참여할 수 있도록 Conference ID를 전달합니다.
11.Host A가 컨퍼런스를 종료하면 Call History 를 생성합니다.
12.통화 내용 녹음이 설정된 경우, MS에 녹음된 파일을 Content Manager 서버로 업로드합니다.

![Sequence Diagram](http://i.imgur.com/giqkR5v.png)

### Design

#### Service Architecture
- 
![](http://i.imgur.com/f9VtAQ4.png)

#### Model Relation
![](http://i.imgur.com/3rADQd8.png)

#### REST API
1. 회원 관리


2. 

### 사용 기술
1. Back-end
	- loopback : open-source Node.js REST API Framework
	- mongodb : CallPlanner 및 Scheduler datasource
	- redis : conference room 관리용 datasource
2. Front-end
	- ionic framework : angular.js 기반의 웹 기술 및 ios,android의 native 기술을 이용한 모바일 SDK Framework
	- angular.js : 웹 앱 개발
	- Bootstrap,css
3. ETC
	- docker : linux 환경에서 서비스를 경량 컨테이너화 하여 빌드 및 배포를 쉽게 할 수 있는 플랫폼
	- AWS Cloud

### Deployment
docker를 이용하여 호스트 혹은 클라우드에 빠르고 쉽게 빌드 및 배포
![](http://i.imgur.com/AFUSvGS.png)

### Test Environment
![](http://i.imgur.com/z4epfA0.png)
### Code Review



