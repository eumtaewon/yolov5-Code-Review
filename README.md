# yolov5-Code-Review

train.py

detect.py 

Code Review

# train.py Review

코드 출처: https://github.com/ultralytics/yolov5 

코드가 지속적으로 업데이트 되기 때문에, 과거의 코드를  Review하는 내용일 수 있습니다.

argparse.ArgumentParser()

argparse.ArgumentParser() 프로그램을 실행시에 커맨드 라인에 인수를 받아 처리를 간단히 할 수 있도록 하는 표준 라이브러리.

ArgumentParser를 사용하면 아래와 같이 프로그램에서 처리할 수 있는 파라미터나 파일명을 실행시에 지정할 수 있음.

![image](https://user-images.githubusercontent.com/104436260/209034184-64bc45a7-f2e8-422f-9ab7-50f0a3145896.png)

train.py parse_opt

![image](https://user-images.githubusercontent.com/104436260/209034405-c9529182-eb48-4ce2-a4fd-d7f7d23ee9b2.png)

모델 Train에 필요한 많은 인자값이 있지만 자주 사용하는 인자는 아래와 같다

해당 인자가 어떠한 내용인지 알고 싶을때는 옆에 help에 적힌 내용을 보면 됨

'--weights'=모델의 가중치 정보가 들어가 있는 파일의 경로
