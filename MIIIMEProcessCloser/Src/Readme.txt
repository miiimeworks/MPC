========================================================================
             Miime Process Closer (MPC™)
             Smart Batch Process Terminator
========================================================================

Terminates running processes according to a user-specified list.

사용자가 지정한 목록에 따라 실행 중인 프로세스들을 종료시킵니다.

========================================================================
Key Features
========================================================================

1. Smart Close
	- Step 1: Request graceful shutdown (Taskkill /im) -> Induces data saving and cleanup.
	- Step 2: Wait for 2 seconds (Graceful Wait).
	- Step 3: Force close if unresponsive (ProcessClose) -> Ensures complete termination.

2. Dynamic Admin
	- Elevates itself to administrator privileges only when necessary via INI settings.
	- Essential for controlling system processes or driver-related applications.

3. Custom Messages
	- Directly configure the message content and whether to display it after a task is completed.

[주요 기능]

1. 스마트 종료 (Smart Close)
   	- 1단계: 정상 종료 요청 (Taskkill /im) -> 데이터 저장 및 정리 유도.
   	- 2단계: 2초간 대기 (Graceful Wait).
   	- 3단계: 응답 없으면 강제 종료 (ProcessClose) -> 확실한 마무리.

2. 동적 관리자 권한 (Dynamic Admin)
   	- INI 설정을 통해 필요할 때만 관리자 권한으로 스스로를 격상시켜 실행.
   	- 시스템 프로세스나 드라이버 관련 앱 제어 시 필수적.

3. 사용자 맞춤 메시지
   -	 작업 완료 후 표시할 메시지 내용과 출력 여부를 직접 설정.

========================================================================
File Organization
========================================================================

MIIIMEProcessCloser
 	├─ Ext/                   			
 	│	│
	│	└─ Res/    
 	│
 	├─ MIIIMEProcessCloser.exe      	실행 파일		/  Executable
 	└─ MIIIMEProcessCloser.ini       	설정 파일		/  Configuration file
______________________________________________________________________________________________________________________

This program was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.
본 프로그램은 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다.

========================================================================
Disclaimer
========================================================================

Provided **"AS IS"**, without warranty.
This is a **private project**. No technical support is provided.
본 프로그램은 **"있는 그대로"** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.
기술 지원은 제공되지 않습니다.

Developer	: MIIIME 
Website		: https://www.miiime.com 
GitHub		: @miiimeworks 
Update		: 2026.10.09