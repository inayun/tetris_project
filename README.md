# tetris_project
### 2013049595 윤인아
### 테트리미노       
##### 1. 모양의 종류: 7가지(기본 테트리미노 모양을 변형)   
'S': S_SHAPE_TEMPLATE   
'H': H_SHAPE_TEMPLATE   
'L': L_SHAPE_TEMPLATE       
'C': C_SHAPE_TEMPLATE        
'I': I_SHAPE_TEMPLATE      
'X': X_SHAPE_TEMPLATE        
'T': T_SHAPE_TEMPLATE      
2. 색깔: 'Light pink' 로 통일
3. 템플릿 5(넓이) * 5(높이)

### 외적요소
1. 폰트 (4가지)   
SMALLFONT = 'shangri.ttf', 18    
BASICFONT = 'shangri.ttf', 25    
BIGFONT = 'shangri.ttf', 100   
DECOFONT = '1942font.ttf', 20   
2. 색상 (4가지)   
WHITE       = (255, 255, 255)   
BLACK       = (  0,   0,   0)    
LIGHTPINK   = (255, 192, 203)   
DARKPINK    = (255, 20 , 147)    
3. 음악 (3가지)  
bgm.mp3   
gameover.mp3     
pause.mp3    
4. 화면 구성    
창 넓이 = 640px  
창 높이 = 400px  
보드 넓이 = 14px  
보드 높이 = 18px  
보드 오른편 = score, level, next 정보  
보드 왼편 = 키 조작에 대한 정보, 점수 계산 정보  
보드 안쪽 = deco문구  
5. 문구    
5.1 게임 오버시  
5.2 paused 시  
5.3 line이 완성될때마다     
5.4 보더안에 데코용    

### 기능
1. 키 조작    
1.1 right_key / d => 블럭이 오른쪽으로 이동    
1.2 left_key / a => 블럭이 왼쪽으로 이동    
1.3 up_key / q / w => 블럭 회전    
1.4 down_key / s => 블럭 서서히 떨어뜨리기    
1.5 space bar => 블럭 한번에 떨어뜨리기    
1.6 p => 게임 일시 중단    

2. 점수계산    
2.1 빈칸없는 줄이 완성되면 한 줄당 score가 1씩 증가    
2.2 score 5점당 level 1씩 증가    

3. 다음에 나올 블럭 미리 보여주기

4. 기본 동작    
4.1 7종류의 블럭이 랜덤하게 위에서 아래로 내려옴    
4.2 특정 키를 눌러 블럭을 회전시킬 수 있음    
4.3 회전한 블럭이 아래에 쌓임    
4.4 한 줄 가득 블럭이 쌓이면 그 줄이 지워짐    

5. 추가 동작    
5.1 게임이 시작되면 배경음악이 반복적으로 나옴(bgm.mp3)    
5.2 줄이 완성되면 'good job'(title), 'you got a score!!'(subtitle) 화면이 나옴    
5.3 level이 올라갈때마다 속도가 점점 빨라짐    
5.4 화면과 함께 효과음(score up.mp3)이 나옴    
5.5 아무 키를 누르면 게임이 다시 재생되고 기본 배경음악이 다시 재생    
5.6 p키를 누르면 'paused'(title), 'restart'(subtitle) 문구가 나오면서 게임이 일시중단됨    
5.7 블럭이 보드에 충돌하면 'game over'(title), 'restart'(subtitle) 화면이 나오면서 게임 중단    
5.8 위 문구와 함께 배경이미지가 바뀜    
5.9 효과음(game over.mp3) 재생 

![start](https://github.com/inayun/tetris_project/blob/master/start.JPG)     
start 화면    
![paused](https://github.com/inayun/tetris_project/blob/master/paused.JPG)     
paused 화면     
![score up](https://github.com/inayun/tetris_project/blob/master/scoreup.JPG)      
score up      
![game over](https://github.com/inayun/tetris_project/blob/master/gameover.JPG)      
game over 화면    
