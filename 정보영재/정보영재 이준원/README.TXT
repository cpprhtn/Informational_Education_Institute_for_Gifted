LogicBuilder 1.71

Tong h. Lim
(tong@islab.kaist.ac.kr)

Dept. of Computer Science, KAIST
   
(c) 1999 - 2001  Tong h. Lim
    tong@islab.kaist.ac.kr
    http://www.digitaljapan.org/
    http://www.digitaljapan.co.kr/


-------------------------------------------------------------------------------


LogicBuilder 사용법


1. LogicBuilder 설치

        1 단계: JRE를 설치한다.
        
                아주 쉽죠? ^^;
                
                JRE.exe를 두 번 누르면 JRE가 설치됩니다.

                만일 JRE.exe가 없을 때는 다음을 따라하면 
                
                JRE를 인터넷에서 다운 받을 수 있습니다.
                
                
                JRE 다운 받는 법:

                  http://www.javasoft.com/products/jdk/1.2/jre/download-windows.html
        
                  로 가면 
        
                  DownLoading Java 2 Runtime Environment including Java Plug-in

                  이라는 페이지가 나옵니다.

                  페이지 중간의 continue 버튼을 누르면,

                  License & Export for Java Runtime Environment 1.2.2-001 

                  이라는 페이지가 나옵니다.
 
                  Agree 버튼을 누르면

                  Download Java Runtime Environment 1.2.2-001
 
                  이라는 페이지가 나오고 

                  HTTP download 버튼을 누르면 하드디스크에 

                  jre1_2_2-001-win.exe (약 5MB 크기)
  
                  라는 이름의 파일이 생깁니다.

                  jre1_2_2-001-win.exe를 실행시키면, JRE가 설치됩니다.


        2 단계: LogicBuilder를 설치한다.

                LogicBuilder.exe 파일을 두 번 눌러 실행시키세요.

                그러면, C:\LogicBuilder 디렉토리에 설치됩니다.
                
                너무 간단한가요? ^^;



2. LogicBuilder 실행

        C:\LogicBuilder 디렉토리를 열면 다음과 같은 파일들이 있어야 합니다.
        
        LogicBuilder    -> 요놈이 실행파일
        Board.class
        LogicBuilder.jar
        Column.class
        LogicCoder.class
        LogicPuzzler.class
        Row.class
        TButton.class
        sample.html
        sample.lim
        
        이 중에서 LogicBuilder를 두 번 누르시면 실행됩니다.
        
        만약, 바탕화면이나 시작 버튼에 '바로가기'를 만들고 싶으시면,
        
        이 LogicBuilder 파일을 복사하시면 됩니다.
        
        LogicBuilder를 두 번 눌러 실행하신 후
        
        File -> Open 메뉴를 선택해서
        
        sample.lim을 불러보세요.
        
        잘 되나요? ^^;

        
        
3. LogicBuilder 사용

        1 단계: 새 로직퍼즐 만들기
        
                File -> New 메뉴를 선택하세요.
                
                1. Size를 선택하세요. 
                
                   박스 내에 원하는 크기가 없으면, 
                   
                   Choose.. 버튼을 눌러 직접 입력하시면 됩니다.
                   
                2. Title를 입력하세요.
                
                   Title은 로직퍼즐을 실행했을때 
                   
                   브라우저 상단에 나올 제목입니다.
                   
                3. Author를 입력하세요.
               
                   Author는 제작자명이나 제작사 이름을 넣으면 됩니다.
                   
                   완성된 로직퍼즐의 상단에는
                   
                   Author: Title
                   
                   형식으로 나타나게 됩니다.
                   
                입력이 모두 끝나면, Ok 버튼을 누르세요.
    
                   
        2 단계: 로직퍼즐 만들기
        
                마우스의 왼쪽 버튼으로 점을 찍어 로직퍼즐을 만드세요.
                
                마우스의 오른쪽 버튼은 만든 점을 지울때 사용합니다.
                
                드래그(끌기) 기능도 있는데, 
                
                버튼을 누르고 마우스를 끌면 칸수가 표시되고
                
                해당하는 칸은 모두 채워지거나(마우스 왼쪽 버튼),
                
                지워집니다(마우스 오른쪽 버튼).                
                
                완성된 로직퍼즐의 숫자를 확인해 보면 정확히 입력되었는지 알 수 있습니다.
                
    
        3 단계: 로직퍼즐 저장하기
        
                File -> Save 메뉴를 선택하세요.
                
                1. File Name을 입력하세요.
                
                Choose.. 버튼을 누르시면 디렉토리가 보이고 원하는 파일면을 선택하거나
                
                입력하시면, Name 창에 반영됩니다.
                
                2. Title을 확인하세요.
                
                1단계에서 적은 Title이 보이시죠?
                
                새로 적어주셔도 됩니다.
                
                3. Author도 확인하세요.
                
                1단계에서 적은 Author와 같은가요?
                
                역시, 새로 적어주셔도 됩니다.
                
    
        4 단계: 만든 로직퍼즐 불러오기
        
                만약, 이미 만든 로직퍼즐을 보고 싶거나,
                
                만들다가 중단했던 로직퍼즐을 이어서 만들고 싶으시면,
                
                File -> Open 메뉴를 선택해서 불러오시면 됩니다.
                

4. LogicPuzzler 사용                   
                
        LogicBuilder는 로직퍼즐을 제작할 수만 있고,
        
        제작된 퍼즐로 게임을 실행할 수는 없도록 되어 있습니다.
        
        실제로 게임을 하고 싶으면 LogicPuzzler를 사용해야 합니다.
        
        LogicBuilder의 File -> Save에서 로직퍼즐을 저장하면
        
        LIM 파일과 HTML 파일이 생깁니다.
        
        LIM 파일은 LogicBuilder에서 사용되는 파일로
        
        해당 로직퍼즐을 언제라도 자유롭게 편집할 수 있는 텍스트파일입니다.
        
        따라서, LIM 파일은 다른 사람이나 인터넷에 공개하시면
        
        누구라도 로직퍼즐 복사, 또는 정답을 알 수 있습니다.
        
        HTML 파일은 LIM 파일의 내용을 암호화한 인터넷 문서입니다.
        
        HTML 파일의 내용은 LogicPuzzler가 아니면, 해독할 수 없습니다.
        
        따라서 HTML 파일을 인터넷에 올리시면 됩니다.
        
        
        예를 들어, LogicBuilder로 sample이라는 로직퍼즐을 만들어 저장하시면,
        
        sample.lim과 sample.html이 생깁니다.
        
        이 sample.html을 두 번 누르시면, LogicPuzzler가 자동으로 실행되면서 
        
        sample 로직퍼즐을 즐길 수 있습니다.
        
        만약 sample 로직퍼즐에 잘못된 점이 발견되거나, 바꾸고 싶을 때는
        
        LogicBuilder를 실행시키고, sample.lim을 불러오면 됩니다.
        
        
        
* 그럼, LogicBuilder와 LogicPuzzler를 사용하여, 즐거운 하루가 되시길 바랍니다.

  만약, 잘 안되거나 의문 사항이 있으시면, 제게 연락주세요.
  
  제 E-mail 주소는 tong@islab.kaist.ac.kr이고,
  
  홈페이지는 http://www.digitaljapan.co.kr/ 입니다.
  
  JRE.exe, LogicBuilder.exe는 http://www.digitaljapan.co.kr/logic/ 에서
  
  항상 최신 버전을 받으실 수 있습니다.
                