# 맥에서 ssh서버 접속하기

윈도우에서는 xshell을 다운로드 받아서 진행했지만, 맥에서는 <strong>터미널</strong>을 통해서 진행한다.
## 1. pem키 등록하기
```shell
chmod 400 /path/to/your-key-name.pem
```
으로 pem키를 등록시킨다.

## 2. ssh서버 접속하기
```shell
ssh -i /path/to/your-key-name.pem ec2-user@ec2-xx-xx-xx-xx.compute-1.amazonaws.com
```
아래와 같은 사진이 뜨면 성공이다 <br><br>
<img width="586" alt="스크린샷 2024-06-06 오후 7 45 30" src="https://github.com/Yanghuiwon22/memo/assets/127187225/98662619-262d-41ec-ac42-fb0645617c6f"><br>
