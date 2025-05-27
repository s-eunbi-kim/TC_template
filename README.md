# TC_template

## PairWise Tool 명령어 : Microsof PICT
* download : https://github.com/microsoft/pict/releases/tag/v3.7.4
* 데이터 입력 : text 파일에 아래의 형식으로 데이터 입력
  ```
  input1 : para1, para2, para3, para4
  input2 : para1, para2, para3
  ```

* 기본 사용 명령어 (pairwise)
  ```
  pict data.txt
  ```
* pict 결과를 result.xls 로 저장 
  ```
  pict data.txt > result.xls
  ```
* 전체 조합 출력 
  ```
  pict data.txt /o:max > result_max.xls
  ```  
