# label_test
public label test code

https://github.com/hunglc007/tensorflow-yolov4-tflite

실제 내용은 참고.txt 에서 긁어 사용하시기 바랍니다.

    # 실행창 열기
    'anaconda prompt' or 'cmd' 창 open ('window key' + 'R')

    # 가상환경 생성
    (base) C:/..../HHI/.vscode> conda create -n <환경명> python=<버전> : 아무거나 가능

    # 가상환경 활성화 (in window)
    (base) C:/..../HHI/.vscode> activate <환경명>

    # 가상환경 내에 requirements 설치
    (환경명) C:/..../HHI/.vscode> pip install -r requirements.txt

    # video file을 해당 data 폴더에 넣기 (folder path는 변형 가능)

    # python detectvideo.py --weights ./checkpoints/yolov4-416 --video 'data/<비디오 파일명>.<type>'

    # 완료 후 /data/result/video 폴더에서 결과 확인 가능

    # 결과물 출력, GPU, pytorch yolov5, fps(frame per second) 변경 가능함.
