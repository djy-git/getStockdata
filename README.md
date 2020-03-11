# Remarks
Python 3.5 (32bit)에서 작동하는 코드로 다른 version에서는 동작을 보장할 수 없습니다.  
대신증권 CreonPlus를 이용하여 데이터를 받아오기 때문에 반드시 CreonPlus가 실행되어 있는지 먼저 확인하고 사용하세요.


# Usage
```
// Change the ROOT_DIR in env.py
$ pip install -r requirements.txt
$ python get_stock.py --unit D
$ python get_stock.py --unit m
```


# TODO
Tick data 구현
