# Multifaceted_Face_Id
한성대학교 인공지능 기말고사 프로젝트

Main Source : https://github.com/harveyslash/Facial-Similarity-with-Siamese-Networks-in-Pytorch/blob/master/Siamese-networks-medium.ipynb


프로그램의 기능 3가지
1. Multifaceted_Face_Id_모델링 코드
2. Multifaceted_Face_Id_회원등록
3. Multifaceted_Face_Id_로그인

Multifaceted_Face_Id_모델링 코드는 Face id의 내부적인 기능을 담당하는 부분, 학습 데이터는 ORL Face DataSet임. 얼굴을 구별할 있는 알려진 모델 중 하나인 파라미터를 공유하는 CNN을 이용하는 샴 네트워크를 모델로 학습

Multifaceted_Face_Id_회원등록은 회원가입을 위한 얼굴 촬영 단계. 카메라를 통해 얼굴 검출 분류기 Harr Cascade로 얼굴 영역만 자르고, 흑백 처리를 해 학습 데이터 전처리를 진행한 후, Name별로 파일로 묶어 저장

Multifaceted_Face_Id_로그인은 회원 확인(테스트) 과정. 카메라에 인식된 얼굴을 등록된 데이터 셋들과 비교 반복하여 화면을 통해 실시간으로 회원으로 인식하는지 알 수 있음
