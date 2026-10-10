# Miime Process Closer (MPC™)

MIIIMEUniWrapper · 미메랩퍼

![OS](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&style=flat-square)
[![Language](https://img.shields.io/badge/Language-AutoIt-orange?logo=autoit&style=flat-square)](https://www.autoitscript.com/site/)
![License](https://img.shields.io/badge/License-Freeware-lightgrey?style=flat-square)

<br>
<img width="559" height="136" alt="001" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Enhanced/Id/Neon/4b_136_1_G.png?raw=true" style="margin-top: 20px; margin-bottom: 20px;">
<br>

Terminates running processes according to a user-specified list.

사용자가 지정한 목록에 따라 실행 중인 프로세스들을 종료시킵니다.


---

## Key Features

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
   - 작업 완료 후 표시할 메시지 내용과 출력 여부를 직접 설정.

---

### File Organization

```text
MIIIMEProcessCloser
 	├─ Ext/                   			
 	│	│
	│	└─ Res/    
 	│
 	├─ MIIIMEProcessCloser.exe      	실행 파일		/  Executable
 	└─ MIIIMEProcessCloser.ini       	설정 파일		/  Configuration file
```  

---

## 🛡️ Security & Anti-virus Info

### [✅ VirusTotal Analysis Report](https://www.virustotal.com/gui/file/6a3ee6833f9006fd02fc28a993e3fd96bf0ffbb855ff3905b88a1fb0d2e0590d?nocache=1)

| Status             | Details                                                                        |
|:------------------ |:------------------------------------------------------------------------------ |
| **Major Vendors**  | **Clean** (Passed by AhnLab V3, Kaspersky, Microsoft, Avast, ESET, etc.)       |
| **Detection Rate** | **8 / 71** (Mostly Heuristic/Generic/Trojan-type flags)                        |
| **Integrity**      | The source code is transparently available for verification in this repository |

> This Program was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.  
> 본 프로그램은 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다. 

**File Checksum (SHA-256) :** `6a3ee6833f9006fd02fc28a993e3fd96bf0ffbb855ff3905b88a1fb0d2e0590d

---

## Disclaimer

Provided **“AS IS”**, without warranty.  
This is a **private project**. No technical support is provided.

본 프로그램은 **“있는 그대로”** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.  
기술 지원은 제공되지 않습니다.

---

## Project Information

**Developer** : MIIIME  
**Website** : https://www.miiime.com  
**GitHub** : [@miiimeworks](https://github.com/miiimeworks)  
**Last Update** : 2026-10-09   

<br>
<img width="64" height="64" alt="002" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Brutal/Logo/Neon/4b_Mium_64_0_G.png?raw=true">  
<br>
<br>
<br>