# 설문조사
* 1일차 설문조사 https://goo.gl/forms/J1OmC42Q0nkeyqx02 
* 4일차 설문조사 https://goo.gl/forms/CXMzRq1x239mKBso2
# Settings

### ■ Eclipse 다운로드
* http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/neon/3/eclipse-jee-neon-3-win32-x86_64.zip&mirror_id=1211

### ■ Junit
* 위 링크의 이클립스 버전 다운받으면 내장되어 있음

* [이클립스] - [개발하려는 프로젝트 루트에서 우클릭] - [Properties] - [Java Build Path] - [Libraries] - [Add Library] - [Junit] 하면 해당 프로젝트에서 Junit 사용가능

### ■ Eclemma 설치
* [이클립스] - [Help] - [Eclipse Marketplace] - [Eclemma 검색후 설치]

### ■ Hamcrest 설정
* [Window] - [Preferences] - [Java] - [Editor] - [Content Assist] - [Favorites] - [New Type]
* org.junit.Assert 추가
* org.hamcrest.CoreMathers 추가

### ■ SonarQube Server 다운로드
* https://sonarsource.bintray.com/Distribution/sonarqube/sonarqube-7.3.zip

### ■ SonarQube Scanner 다운로드
* https://sonarsource.bintray.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-3.2.0.1227-windows.zip

* [내 PC] - [속성] - [고급 시스템 설정] - [환경변수] - [시스템 변수] - [새로만들기]
  변수이름 SONAR_SCANNER
  변수값 sonar scanner 설치 위치

* [내 PC] - [속성] - [고급 시스템 설정] - [환경변수] - [시스템 변수] - [Path] - [편집] - [새로만들기]
  %SONAR_SCANNER%\bin
  추가

* sonar-project.properties 파일있는곳에서 sonar-scanner.bat 실행해서 로컬 SonarQube 서버에 분석데이터  

### ■ Tomcat 다운로드
* http://apache.mirror.cdnetworks.com/tomcat/tomcat-7/v7.0.90/bin/apache-tomcat-7.0.90-windows-x64.zip

### ■ 아크로뱃 리더
* https://get.adobe.com/kr/reader/download/?installer=Reader_DC_2018.009.20044_Korean_for_Windows&os=Windows%2010&browser_type=KHTML&browser_dist=Chrome&dualoffer=false&mdualoffer=true&cr=true&stype=7678&d=McAfee_Security_Scan_Plus&d=McAfee_Safe_Connect
