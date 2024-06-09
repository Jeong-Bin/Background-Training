# Background-Training

## nohup
nohup 명령어를 이용하여 실행할 명령어 파일의 권한은 755(rxwrx-rx-) 이상이어야 한다. </br>
chmod 755 test.sh

nohup train.py & </br>
nohup train.py 1> standard.out 2> standard.err & (표준 출력 및 표준 에러 파일 변경하기) </br>
nohup train.py > standard.log 2>&1 & (표준 출력 및 표준 에러를 같은 파일에 쓰기) </br>
nohup train.py > /dev/null & (표준 출력 X)

% ps -ef | grep train.py (백그라운드에서 실행되고 있는지 확인)


## putty
