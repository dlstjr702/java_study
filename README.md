# java_study_1week


--------------------------------------------
<20260511 수업자료><br>
<img width="1210" height="499" alt="jdk설치방법" src="https://github.com/user-attachments/assets/33ebdf21-f250-4e07-9381-cfb1f86b4e6b" />

자바 다운로드(오라클)<br>
https://www.oracle.com/java/technologies/downloads/#java11-windows<br>

프로그램 설치경로(JDK11설치)<br>
C:\Program Files\Java\jdk-11.0.31\<br>

시스템환경변수> 시스템변수창> 새로만들기<br>
>시스템변수 JAVA_HOME 새로만들기 >path설정(%JAVA_HOME%\bin)<br>

프로그램 설치경로(JDK17설치)<br>
C:\Program Files\Java\jdk-17.0.19\

프로그램 설치경로(JDK21설치)<br>
C:\Program Files\Java\jdk-21.0.11\

Sample.java 소스파일 생성<br>

/* 코드
public class Sample{<br>
	public static void main(String[] args){<br>
		System.out.println("Hello World");<br>
	}<br>
}<br>
*/

/*프롬프트 단축어*/
cls = 프롬프트 초기화<br>
cd  =  디렉토리 변경<br>
chcp = 현재cmd 문자 인코딩<br>
/*
/*컴파일 작업후 클래스 파일 생성 */<br>
C:\Class\JavaClass>javac Sample.java <<컴파일후 클래스파일생성<br>
C:\Class\JavaClass>java Sample  <<뒤에 .java는 맞는표현이 아님<br>
Hello World(출력결과물)<br>
*/

/*이클립스 설치*/
https://www.eclipse.org/downloads/packages/
<img width="910" height="680" alt="화면 캡처 2026-05-11 123706" src="https://github.com/user-attachments/assets/5b037171-65ea-4e74-9b8e-9fa492d966d1" />

windows --- x86_64버전파일로 설치<br>
bin폴더는 컴파일된 파일(class파일) 저장소<br>

<img width="910" height="680" alt="화면 캡처 2026-05-11 123706" src="https://github.com/user-attachments/assets/d1a37bcd-1b84-431a-8f4e-17bf4045666f" />
<img width="1450" height="750" alt="화면 캡처 2026-05-11 141825" src="https://github.com/user-attachments/assets/5c87b127-3b31-4b30-a33c-0c30aaa4a5bf" />
<img width="635" height="552" alt="화면 캡처 2026-05-11 141852" src="https://github.com/user-attachments/assets/9bc84f32-9b5f-4924-babb-2f2fd7ee74fb" />
<img width="683" height="570" alt="화면 캡처 2026-05-11 142053" src="https://github.com/user-attachments/assets/e54a9be8-0236-4f7d-a462-4365d969b4d3" />
<img width="671" height="617" alt="화면 캡처 2026-05-11 142253" src="https://github.com/user-attachments/assets/50754364-e945-451f-b493-5b62cc5c97c4" />
<img width="1046" height="831" alt="화면 캡처 2026-05-11 142511" src="https://github.com/user-attachments/assets/67784a3c-cb23-4979-9ea7-ac875261d3a5" />
<img width="730" height="744" alt="화면 캡처 2026-05-11 142647" src="https://github.com/user-attachments/assets/936dced6-4f3f-45ef-bb33-7ab825dc9042" />
<img width="1266" height="740" alt="화면 캡처 2026-05-11 143009" src="https://github.com/user-attachments/assets/fc318e37-443b-4290-b3e7-1c69f9ba609d" />

/*이클립스 단축키*/<br>
//단축키 목록 : ctrl+shift +l
ctrl+ space = 자동완성 명령어<br>
ctrl+ alt+ 방향키/아래or위 = 아래/위 한줄 복사<br>
ctrl+ / = 토글주석<br>
ctrl+ shift + / = 문장주석<br>
Ctrl + F11: 컴파일 실행<br>
trl + 7 or / : 토글 주석 처리 <br>
Alt + Shift + J: 주석 처리<br>
Ctrl + F: 단어 변경시(replace)<br>
Ctrl + A 입력후 Ctrl + I = 자동 들여쓰기

<img width="1218" height="754" alt="화면 캡처 2026-05-11 154129" src="https://github.com/user-attachments/assets/50ae266f-dc0f-4084-ab44-df4b62e509d1" />
<img width="1069" height="749" alt="화면 캡처 2026-05-11 153711" src="https://github.com/user-attachments/assets/525eb158-ad7a-4561-8b63-24e0b2cadf07" />
<img width="529" height="710" alt="화면 캡처 2026-05-11 154626" src="https://github.com/user-attachments/assets/5a5eb380-f91e-4f3c-9248-2ea81ee5f262" />
<img width="1020" height="739" alt="화면 캡처 2026-05-11 154326" src="https://github.com/user-attachments/assets/92c51d03-4140-460b-b16b-e22cb1dd7540" />
<img width="946" height="579" alt="화면 캡처 2026-05-11 154138" src="https://github.com/user-attachments/assets/50118e28-fe03-4769-b0b6-d34190b7c91f" />
<img width="1149" height="752" alt="화면 캡처 2026-05-11 162937" src="https://github.com/user-attachments/assets/e011bb06-4215-441c-a4e0-5eb35baa1525" />
<img width="529" height="710" alt="화면 캡처 2026-05-11 154626" src="https://github.com/user-attachments/assets/e4eacf47-d0fb-495e-88be-c79be77b8595" />
<img width="1020" height="739" alt="화면 캡처 2026-05-11 154326" src="https://github.com/user-attachments/assets/6a4a628c-205f-4616-a0b7-018e22320c3e" />


windows > show view = 닫힌창 열기<br>



/*
		 * 1. 자바는 객체 지향 프로그래밍 언어이기 때문에 반드시 프로그램의 시작을 하는 시작개체(==객체,클래스,물건)가 필요하다.<br>
		 * 2. 자바에서는 클래스 선언 형식<br>
		 * 		public = 접근지정자<br>
		 *      class  = 클래스 선언예약어/클래스 뒤에는 클래스명<br>
		 *      (클래스명은 자바파일명과 동일해야하면 클래스명은 대문자로 시작해야한다)<br>
		 *      main   = 메서드(함수)<br>
		 *      <br>
		 * 		public class Ex02{<br>
		 * 		}<br>
		 * 		접근지정장 클래스예약어 클래스명{}<br>
		 * 3.프로그램의 시작/종료(진입점)하는 기능의 함수(메서드)가 필요하다<br>
		 * 3-2.<br>
		 * java Sample 실행(터미널 실행)<br>
		 * Ctrl + F11  실행(이클립스 실행) > 시작개체(main)> main메서드<br>
		 * 4. 자바에서 메서드(함수) 선언 형식<br>
		 * [접근지정자]  [기타제어자]  리턴자료형 메서드명(매개변수){<<<평가 정답 <br>
		 *  []대괄호는 생략가능하다라는 말이다.<br>
		 *  접근지정자와 기타제어자를 합한말을 modifiers(한정자)<<암기안해도 읽어두기만하기!!<br>
		 *  <br>
		 *  [return 반환값;] 반환값이 없을때 생략가능함 void가 붙은거 확인!!<br>
		 * }<br>
		 * public   static  void    main(String[] args) {<br>
		 * }<br>
		 * <br>
		 * 
		 * 4-2. 메서드(함수) 3가지<br>
		 *   1) 기능: 프로그램 시작/종료 일(기능)을 하는 함수<br>
		 *   2) 매개변수: <br>
		 *   3) 반환값(=리턴값)<br>
*/



--------------------------------------------
<20260512 수업자료>

System.in = 입력<br>
System.out = 출력<br>
<br>
<문자열 출력><br>
// 한문자 나타낼 때는  '김'<br>
// 자바에서 문자열을 나타낼 때는 ""<br>
	System.out.println("류호훈");<br>
    System.out.println();// 출력X +  줄바꿈(개행)<br>
    System.out.println("이시연");<br>
    System.out.println("장미성");<br>
<br>
<br>
// JDK = JRE + 개발도구( bin폴더: java.exe, javac.exe 등등 )<br>
// ㄴ = JVM  + 클래스라이브러리 <br>
<br>
>문자열<br>
String<br>
한문자 출력 ''<br>
문장열 출력 ""<br>

<기본형><br>
- 숫자형<br>
> 정수형(byte,short,char,int,long)<br>
> 실수형(float,double)<br>
<br>
- 논리형<br>
> boolean<br>
<br>
<참조형><br>
배열, 클래스(String, 열거형), 인터페이스><br>
<br>
byte(127), short(32767), int(21억), logn(900경)<br>
<br>
변수 및 상수(final)<br>
- 상수사용시 대문자로 사용<br>
- Camel 표기법불가 전체 대문자사용/두문장인경우 _로 구분<br>
<br>
이스케이프문자<br>
\"  = ">>> "\ <<<" 이상태로<br>

출력문<br>
System.out.println();<br>
System.out.print();<br>
System.out.printf("출력형식(String타입)", 출력할값..  );<br>
System.out.printf("이름은 \"%s %s\"입니다.",lastName,firstName);<<ex<br>
System.out.printf("이름은 \"%s\"이고, 나이는 '%d'살이고, 학점은'%c'이고, 성별은 %b입니다.",name,age,grade,gender);<<ex<br>
%s = 문자열<br>
%d = 숫자열<br> 10진수
%o = 숫자열<br> 8진수
%x = 숫자열<br> 16진수
%c = char숫자열<br>
%b = 자료형<br>
%f = 실수형<br>

자동형변환
cast문법 () <<<  ex) (short)(100+30+20)

--------------------------------------------
<20260513 수업자료>
https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/Formatter.html#syntax

[conversion]
%s = 문자열<br>
%d = 숫자열<br> 10진수
%o = 숫자열<br> 8진수
%x = 숫자열<br> 16진수
%c = char숫자열<br>
%b = 자료형<br>
<img width="614" height="257" alt="화면 캡처 2026-05-13 142553" src="https://github.com/user-attachments/assets/410bfae8-8994-4dcc-b34e-f01162421d8e" /><br>

%f = 실수형<br>

System.out.printf("평균 : [%10.2f]\n",avg);
>양수를 입력하면 우측정렬 음수를 입력하면 좌측정렬 .2소수점 두번째까지출력

System.out.printf("%1$s_%1$s_%1$s",name);
>name이라는 변수 한개를 여러개 출력하는경우

[flag]
[음수,실수 표현방법]
[지역변수]
[format]

// 1. br 객체 생성



		BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

		String name;      
		int kor = 0 , eng = 0 , mat = 0;
		int tot = 0;  
		double avg = 0;

		//이름
		System.out.print("> 이름 입력: ");
		name = br.readLine();

		//국어
		System.out.print("> 국어 입력: ");
		kor = Integer.parseInt( br.readLine());

		//영어
		System.out.print("> 영어 입력: ");
		eng = Integer.parseInt( br.readLine());

		//수학
		System.out.print("> 수학 입력: ");
		mat = Integer.parseInt( br.readLine());

		//총점 구하기
		tot = (int)(kor+eng+mat);
		
		//평균구하기
		avg = tot/3D;
		
		//값 전부 출력하기
		System.out.printf("이름: %s\n국어:%d\n영어:%d\n수학:%d\n총점:%d\n평균:%f\n"
				, name, kor, mat, eng, tot, avg);


[타입 변환]
<img width="721" height="411" alt="화면 캡처 2026-05-13 155102" src="https://github.com/user-attachments/assets/5bafefe5-e320-43f2-8322-5db5b06dd3f5" /><br>


[연산자]<br>
- 산술연산자<br>
- 비교연산자<br>
- 논리연산자<br>
- 대입연산자<br>
- 조건연산자<br>
<br>


[조건문]<br>
-조건문 (if,swith,while)<br>
-반복문(for)<br>


--------------------------------------------
<20260514 수업자료>

[조건문 테스트 및 복습]<br>
- if, for, while 문<br>



=====================================================================================
/*<br>
* 3. 이름(String), 나이(byte), 키(double), 성별(boolean) 입력받아서 출력.<br>
*    ( 조건: Scanner 사용하기 ) <br>
*    <br>
*    입력형식:<br>
*    > 이름 나이 키 성별 입력 ? 홍길동 20 178.89 true<br>
*    <br>
*    출력형식:<br>
*    > 이름:홍길동, 나이:20살, 키:178.89cm, 성별:남자<br>
*/<br>
<br>
<br>
String name;<br>
int age;<br>
double height;<br>
boolean gender;<br>
<br>
<br>
Scanner scanner = new Scanner(System.in);<br>
<br>
System.out.printf(">이름 나이 키 성별 입력 ?");<br>
name = scanner.next();//String 입력받을때는 next() nextLine()<br>
age = scanner.nextInt();<br>
height = scanner.nextDouble();<br>
gender=scanner.nextBoolean();<br>
<br>
<br>
System.out.printf("> 이름:%s, 나이:%d살, 키:%.2fcm, 성별:%s \n",name, age, height, gender?")
=====================================================================================
		int min = n>m ? m:n;<br>
		int max = Math.max(n, m);<br>
		//for문안에 Math.max /Math.min 선언하지말기 로직은 맞으나 성능/속도가 늦어짐<br>
		for (int i = min;  i<= max; i++) {<br>
			sum += i;<br>
			if (i < m) {<br>
				System.out.print(i + "+");<br>
			}else {<br>
				System.out.print(i);<br>
			}<br>
		}//for<br>
=====================================================================================
// 람다(Labda)와 스트림(Stream)<br>
int sum = IntStream.rangeClosed(1, 10).sum();<br>
System.out.println(sum);<br>


[반복문]
- do while문
- continue
- break


[배열]
-array


- 로또 출력하기  ( 작업 )
- 가위바위보 (작업)
- 가위바위보 추가작업 한게임에 100원 초기 돈 입력 가위바위보 지면 100원차감 이기면 100원 누적
- 이기고 누적되면 게임계속할껀지 물어보기
- 코인이 없어지면 게임종료






--------------------------------------------
<20260515 수업자료>
