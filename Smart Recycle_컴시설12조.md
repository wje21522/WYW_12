
#**Smart Recycle**  






과  목   명| 컴퓨터 시스템 기초 설계
--------  | ---
담당교수 | 강승우 교수님
분   반     | 01분반


조  | 12조
----|-----
2013136068 |  양희혜
2013136071   |우재은
2013136072  | 원주연

![한기대로고](https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xpt1/v/t1.0-9/12122630_1088656004477733_1675076841412409785_n.jpg?oh=3b370f024d84427e2f88d7ec68178627&oe=56ED94A5&__gda__=1461462565_27440ce6126b6040210b10f5538704d1)

#-목차-

1.개요  | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ3
----|-----
1.1    문제 상황 | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ3
1.2    시스템의 필요성  |ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ3
1.3   문제 정의(5 whys) | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ4
1.4   시스템 요구사항 | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ4
1.5    핵심 아이디어  |ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ5
1.6   전체 시스템 구조  | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ5
1.7   기존의 방법/제품/서비스/시스템|ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ5
1.8   시스템 차별성 및 장점   | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ7

2.시스템 설계  | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ7
----|-----
2.1    시스템의 목적 | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ7
2.2    시스템 구조  |ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ7
2.3   시스템 기능 | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ8
2.4   시스템 구성요소 및 각 기능 | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ8
2.5    시스템 동작흐름  |ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ9
2.6   시스템 전체 구조  | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ10

3.핵심 구성요소 상세 설계  |ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ11
----|-----
3.1 클래스 정의(멤버변수, 멤버 함수의 기능 정의)| ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ11
3.2 멤버 함수의 입력/출력  | ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ12
3.3   함수 수도코드 |  ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ12

4.구현에 필요한 기술 및 개발환경 조사|ㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍㆍ16
----|-----


3. 핵심 구성요소 상세설계
===================
##3.1 클래스 정의(멤버변수, 멤버 함수의 기능 정의)
###3.1.1 회전 기능


| Class Rotation  |        | 로봇팔의 전체적인 회전 제어   |
| :------- | :---- | :--- |
| 멤버 변수 | double r_angle  | 회전각도  |
| | double distance  |로봇 팔과 쓰레기 거리|
|  | int plastic = 1 |플라스틱은 1로 저장 |
|| int glass_bottle = 2  |병은 2로 저장|
| | int result  | 판별한 결과|
| |double x |판별 결과 수집통(플라스틱, 캔, ...)의 위치 |
| |double y |판별 결과 수집통의 y위치|
| |double R_x    | 쓰레기 값의 x 위치|
| | double R_y  | 쓰레기 값의 y 위치|
| | double R_dis  |로봇의 중심과 쓰레기 값의 거리 |
| | double R_res_dis  | 로봇의 중심과 수집통 간의 거리 |


###3.1.2 관절 제어 기능

| Class joint |   | 로봇팔 관절 제어 |
| :------- | :---- | :--- |
| 멤버 변수 | double robot_x  | 로봇 팔 x 위치 값|
| |double robot_y |로봇 팔 y 위치 값|
| | double robot_z|로봇 팔 z 위치 값 |
| | double joint_top_y|첫 번째 관절(어깨)의 y축 좌표|
| | double joint_top_z | 첫 번째 관절(어깨)의 z축 좌표|
| |double joint_mid_y|두 번째 관절(팔꿈치)의 y축 좌표 |
| |double joint_mid_z |두 번째 관절(팔꿈치)의 z축 좌표|
| |double joint_bot_y  | 세 번째 관절(손목)의 y축 좌표|
| |double joint_bot_z|세 번째 관절(손목)의 z축 좌표|
| 멤버 함수 | void init()  | y축 좌표와 z축 좌표 초기화 함수|
| |void crash()|충돌을 위한 체크 함수|
| |void move(x, y, z)|관절 이동을 위한 함수|


###3.1.3. 손가락 제어 기능

| Class pick |   | 로봇팔 손가락 제어|
| :------- | :---- | :--- |
| 멤버 변수 | double f1_angle |첫번째 손가락의 움직일 각도|
| |double f2_angle|두번째 손가락의 움직일 각도|
| | double f3_angle |세번째 손가락의 움직일 각도|
| |double volt |첫 번째 관절(어깨)의 y축 좌표|
| | double true_f1_ang | 첫번째 손가락이 멈추는 각도|
| |double true_f2_ang |두번째 손가락이 멈추는 각도|
| |double true_f3_ang;|세번째 손가락이 멈추는 각도|
| 멤버 함수 | void init_1() | 집게손 각도 초기화. 쓰레기를 투하하는 함수|
| | void init_2()|집게손 각도 초기화. 쓰레기를 투하하는 함수|
| | void init_3()|집게손 각도 초기화. 쓰레기를 투하하는 함수|
| | void Pick()  |쓰레기 집는 함수|

##3.2  멤버 함수의 입력 / 출력

|함수 이름  |   입력  | 출력   |
| :------- | :---- | :--- |
| void R_init() | 회전각도 | 초기화된 회전각도|
| void R_trash()| 쓰레기 위치 |쓰레기를 향하는 각도|
|void recycle()  |쓰레기 판별된 결과 |해당 수집통을 향하는 각도 |
|void init() | 어깨, 팔꿈치, 손목|어깨, 팔꿈치, 손목 초기화|
|void crash() |손목 z축 좌표| 충돌 체크 여부|
| void move(x, y, z)|쓰레기의 위치 |로봇팔의 x,y,z(쓰레기에) 위치 |
|void init_1() |집게손1 각도 |손가락이 벌려진 각도 초기화|
|void init_2() |d집게손2 각도  | 손가락이 벌려진 각도 초기화|
|void init_3() | 집게손3 각도 | 손가락이 벌려진 각도 초기화|
|void Pick()  | 집게1,2,3의 각각의 압력 |물체 잡기 |

##3.3 함수 수도코드
###3.1.1 Class Rotation

```javascript
double r_angle//회전각도

double distance //로봇 팔과 쓰레기 거리

int plastic = 1
int glass_bottle = 2
    ㆍ
    ㆍ
    ㆍ
    ㆍ
int result // 판별한 결과

double x //판별 결과 수집통(플라스틱, 캔, ...) 의 x위치
double y //판별 결과 수집통의 y위치

double R_x // 쓰레기 값의 x 위치
double R_x // 쓰레기 값의 y 위치
double R_dis // 로봇의 중심과 쓰레기 값의 거리
double R_res_dis // 로봇의 중심과 수집통 간의 거리 

void R_init() { //로봇 팔 회전각도 초기 값
   r_angle=0
   
   return r_angle

}

void R_trash() { //쓰레기로 향할 각도 측정하는 함수

   R_x = 100 – trash_x
   R_y = trash_y

   R_dis = R_x / (R_y^2 + R_x^2)^(1/2)

   r_angle = arccos(R_dis)

   return r_angle
}

// 쓰레기 좌표를 이용해서 로봇 본체의 중심과 거리를 구한다. 그리고 그 거리를 이용해서 각도를 구한다. 그 각도로 회전시킨다.

void recycle() { //쓰레기 별 알맞은 쓰레기통으로 위치하는 함수

 switch(result) {
    case 1:
        x = 50
        y = -50

        x = 100 – x
        R_res_dis = x / (y^2 + x^2)^(1/2)

        r_angle = arccos(R_res_dis)
        break;

    case 2:
        ㆍ
        ㆍ
        ㆍ
        ㆍ
        ㆍ
        ㆍ
        ㆍ
        ㆍ

   return r_angle
}
// 판별이 된 정보를 받아 들인다. 그리고 그 판별결과의 수집통을 찾아서 그 거리를 계산하고 각도를 회전한다. 
```


###3.1.2 Class Joint

```javascript
double joint_top_y // 첫 번째 관절(어깨)의 y축 좌표
double joint_toup_z
double joint_mid_y // 두 번째 관절(팔꿈치)의 y축 좌표
double joint_mid_z
double joint_bot_y // 세 번째 관절(손목)의 y축 좌표
double joint_bot_z

void init() //y축 좌표와 z축 좌표 초기화
{
   joint_top_y = 0; // 첫 번째 관절(어깨)의 y축 좌표 초기화
   joint_top_z = 0;
   joint_mid_y = 0; // 두 번째 관절(팔꿈치)의 y축 좌표
   joint_mid_z = 0;
   joint_bot_y = 0; // 세 번째 관절(손목)의 y축 좌표
   joint_bot_z = 0;
}

void crash()//충돌을 위한 체크
{
//바닥을 치지 않았는지 체크
      if(joint_bot_z<0) {
         return false;
      }
}

void move(x, y, z) // y축좌표, z축 좌표만큼 움직이는 함수
{
    while(x == 1) {
    
        if( 로봇손의 x 위치가 쓰레기 x좌표와 같고 로봇손의 y의 위치가 쓰레기 y값이면) {
            x = 0
            break
        }
        else {
            어깨각도 += 1
            팔꿈치각도 += 2
        }
    }

    while(x == 1) {
        if(물체 Z축 좌표라면){	
            x = 0
            break
        }
        else{
	어깨각도 -= 1
             팔꿈치각도 -= 2
	robot_z -= 1
        }
    }
}
```

###3.1.2 Class Pick

```javascript
double f1_angle; //첫번째 손가락의 움직일 각도
double f2_angle;
double f3_angle;

double volt; //압전형 

double true_f1_ang; //첫번째 손가락이 멈추는 각도
double true_f2_ang;
double true_f3_ang;

init_1()// 집게손 각도 초기화. 쓰레기를 투하하는 함수
{
   f1_angle = 90;
}
init_2()// 집게손 각도 초기화. 쓰레기를 투하하는 함수
{
   f2_angle = 90;
}
init_3()// 집게손 각도 초기화. 쓰레기를 투하하는 함수
{
   f3_angle = 90;
}
   
Pick() //쓰레기 집는 함수
{
    //이미 관절함수로 쓰레기 위치와 로봇팔 위치는 일치한 상태
    f1_angle = 90;
    f2_angle = 90;
    f3_angle = 90;

    for(int i = 90; i < 0; i--) {
        while ( f1_angle < 0 ) {
            if(압력이 없으면) {
                f1_angle -= 1
                break
            }
            else { // 압력이 있으면
                true_f1_ang= f1_angle 
                f1_angle  = 0 //x1 멈춤
            }
        }
    
        while ( f2_angle < 0 ) {
            if(압력이 없으면) {
                f2_angle -= 1
                break
            }
            else {
                true_f2_ang= f2_angle 
                f2_angle  = 0 //x2 멈춤
            }
        }
    
        while ( f3_angle < 0 ) {
            if(압력이 없으면) {
                f3_angle -= 1
                break
            }
            else {
                true_f3_ang = f3_angle 
                f3_angle  = 0 //x3 멈춤
            }
        }
    }
}
```
