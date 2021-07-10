# Dicom 샘플 데이터를 이용하여 3D 모델 편집 및 추출

1. Crop Enable과 Display ROI를 활성화 시켜준다.    
<img src="/chapter2/ch2_1.png" width="70%" height="70%" title="" alt=""></img><br/>
2. 빨간색으로 표시한 핀들을 조정하여 3d model 중 원하는 부분만 남겨보자   
<img src="/chapter2/ch2_2.png" width="70%" height="70%" title="" alt=""></img><br/>
<img src="/chapter2/ch2_3.png" width="70%" height="70%" title="" alt=""></img><br/>
3. Crop Volume 설정 창으로 간 후 Apply 클릭, Dicom파일(CT사진)에도 수정사항이 가해진 것을 볼 수 있다.
<img src="/chapter2/ch2_4.png" width="70%" height="70%" title="" alt=""></img><br/>
<img src="/chapter2/ch2_5.png" width="70%" height="70%" title="" alt=""></img><br/>
4. 3D 모델링을 위한 CT 편집을 위해 Volume을 비활성화  
<img src="/chapter2/ch2_6.png" width="70%" height="70%" title="" alt=""></img><br/>
<img src="/chapter2/ch2_7.png" width="70%" height="70%" title="" alt=""></img><br/>
5. Editor로 이동   
<img src="/chapter2/ch2_8.png" width="70%" height="70%" title="" alt=""></img><br/>
6. ThresholdEffet 클릭 ->  ThresholdEffect를 Bone으로 선택 ->  Threshold Range를 146으로 조정 -> Apply 클릭   
<img src="/chapter2/ch2_9.png" width="70%" height="70%" title="" alt=""></img><br/>
7. MakeModelEffect 클릭 -> 모델이름 지정 -> Apply 클릭 (렌더링 되는데 시간 소요 gpu 권장)
<img src="/chapter2/ch2_10.png" width="70%" height="70%" title="" alt=""></img><br/>
8. vtk파일을 stl파일로 저장한다.   
<img src="/chapter2/ch2_11.png" width="70%" height="70%" title="" alt=""></img><br/>
9. 렌더링된 stl파일을 윈도우10 기본 3d뷰어를 통해 불러들인 모습이다.   
<img src="/chapter2/ch2_12.png" width="70%" height="70%" title="" alt=""></img><br/>

이렇게 chapter1~chapter2에 걸쳐 3d모델링 데이터를 조작 편집 추출하는 과정을 알아봤다.   
다음엔 뭘 해볼까?
