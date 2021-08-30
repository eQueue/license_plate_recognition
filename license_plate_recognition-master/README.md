# License Plate Recognition (차량 번호판 인식기)

- Recognize location of plate
- Recognize characters in plate using [tesseract](https://github.com/tesseract-ocr/tesseract)

**Click image to see [demo video](https://youtu.be/PpTl7xxGXh4)!**  
[![result.png](https://github.com/kairess/license_plate_recognition/raw/master/19%EC%98%A47777.jpg)](https://youtu.be/PpTl7xxGXh4)

## 위의 프로젝트의 인식 개선방법
- 현재 프로젝트는 OCR 라이브러리를 활용한 방법으로 한글과 숫자에 한정한 정확도 향상이 가능할 것으로 보임 



## Dependencies
- Python 3+
- pytesseract 4.0
  - [kor.traindata](https://github.com/tesseract-ocr/tessdata/blob/master/kor.traineddata)
- OpenCV
- numpy
- matplotlib
