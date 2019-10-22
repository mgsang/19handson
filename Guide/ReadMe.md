# Hands-On 랩 접속 방법 가이드

**Step by Step Hands-On 테스트 랩 접속/설정 가이드**

#### Step 1# ATD 메인 페이지 접속<br>
1-1. 인터넷 브라우져 실행 (Google Chrome, Microsoft Windows Explore, Firefox,.)<br>
1-2. URL 입력 (수신 이메일 URL 입력)
```html
http://adc-topology.arista.com/api/topology/XXXXX
```

#### Step 2# ATD 랩 가이드 다운로드<br>

![img1](https://github.com/mgsang/19handson/blob/master/Guide/images/starting.jpg)<br>
2-1. Start Topology 클릭하여 장비 실행 (Stopped -> Pending -> Running, 30초 ~ 1분 소요되며 8시간 이후 자동 정지)<br>
2-2. Click Here To Access Topology 클릭하여 토폴로지 접속<br>
![img2](https://github.com/mgsang/19handson/blob/master/Guide/images/step3.png)<br>
2-3. Lab Guides(PDF) 클릭하여 가이드 파일 다운로드<br>

메뉴 | 설명
---|:---:
`Lab Guides(PDF)` | 랩 접속 / 설정 가이드
`Lab Frontend` | 웹 브라우져로 랩 장비 접속
`CVP` | CloudVision Portal 접속
`CVP Telemetry` | CloudVision Portal 접속

#### Step 3# ATD 랩 원격 접속 (SSH)

```python
ssh arista@ip address
password : arista
```
#### Step 4# 테스트 랩 시나리오 선택 및 장비 접속
![img3](https://github.com/mgsang/19handson/blob/master/Guide/images/connecting_ssh.png)<br>

번호 | 설명
---|:---:
`1 ~ 9` | 네트워크 장비
`21` | 설정 초기화
`22 ~ 27` | 시나리오 별 자동 설정

#### Step 5# 다운로드 받은 ATD 랩 가이드를 보고 설정
