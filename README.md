#  Virus Scanning Setup and Automation using ClamAV in Linux
在 Linux 系統中使用 ClamAV 進行病毒掃描與自動化設定

---------

<h2>Outline 簡介</h2>

This project demonstrates how to install, configure, and test the ClamAV antivirus software in a Kali Linux environment. The lab includes installing ClamAV using command-line tools, scanning files with the EICAR test virus, and configuring scheduled scans with Crontab.

本專案展示如何在 Kali Linux 環境中安裝、設定並測試 ClamAV 防毒軟體，內容涵蓋透過命令列安裝 ClamAV、使用 EICAR 測試病毒檔進行掃描，以及利用 Crontab 安排排程掃描。

---------

<h2>Key Learning Outcomes 主要學習成果</h2>

* Install and configure ClamAV with GUI support. (安裝並設定含圖形介面的 ClamAV)

* Use the EICAR test virus to validate ClamAV detection. (使用 EICAR 測試病毒驗證 ClamAV 偵測功能)

* Run manual virus scans and interpret results. (執行手動掃描並解讀結果)

* Automate regular scans using Crontab. (透過 Crontab 自動化排程掃描)
---------
* Install and configure ClamAV using apt (使用 apt 安裝並設定 ClamAV)

* Validate detection capability with the EICAR test virus (利用 EICAR 測試病毒驗證偵測能力)

* Run manual virus scans and interpret results (執行手動掃描並解讀結果)

* Automate periodic scans using Crontab (透過 Crontab 自動化排程掃描)


<h2>Security and Administrative Implications 資安與系統管理層面涵義</h2>

This task introduced us to real-world cybersecurity practices and automated system maintenance. We learned how to implement scheduled protection routines and handle potential threats using CLI tools, which are essential in any professional IT environment.

這項練習讓我們接觸到實際資安操作與系統維護自動化的流程。我們學會如何實作排程式防護機制，並透過指令列工具處理潛在威脅，這些都是專業 IT 環境中不可或缺的技能。

---------

<h2></h2>

<h2>Tools and Concepts Covered 涵蓋工具與概念</h2>

| Aspect <br/>(面向)       | Learning content and purpose <br/>(學習內容與目的)                           |
| -------- | --------------------------------- |
| System management <br/>(系統管理)     | Use Synaptic, modify `.profile`, set PATH <br/>(使用 Synaptic、修改 `.profile`、設定 PATH) |
| Antivirus practice <br/>(防毒實務)     | Install ClamAV, antivirus test and manual scan <br/>(安裝 ClamAV、防毒測試與手動掃描)               |
| Information security test <br/>(資安測試)     | Use a legitimate virtual virus (EICAR) to test the scanning effect <br/>(使用合法的虛擬病毒 (EICAR) 測試掃描效果)          |
| Automated job management <br/>(自動化作業管理)  | Set up Cron tasks to perform scans regularly <br/>(設定 Cron 任務，定期執行掃描)                 |
| Information security practical thinking <br/>(資訊安全實務思維) | Establish a general defense cycle for antivirus systems and strengthen operation and scheduling capabilities<br/>(建立防毒系統的一般防禦週期，強化操作與排程能力)           |

---------

<h2>Materials and Methods 材料與方法</h2>

[Environment]
* Oracle VM VirtualBox (VirtualBox 虛擬機)</b>
* Kali Linux OS (Kali Linux 作業系統)</b>
* ClamAV antivirus suite (ClamAV 防毒套件)</b>

[Tasks]
* Install ClamAV (安裝ClamAV)</b>
* Download EICAR Test Virus (下載 EICAR 測試病毒)</b>
* Run ClamAV Scan (執行 ClamAV 掃描)</b>
* Schedule Automatic Scans with Crontab (使用 Crontab 設定排程掃描)</b>

---------

<h2>Practice 實踐</h2>

<p align="center">
<b>Task 1: Install ClamAV<br/>(安裝 ClamAV)</b><br/>
<img src="https://i.imgur.com/KzswklJ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
<br />
<b>Task 2: Download EICAR Test Virus<br/>(下載 EICAR 測試病毒) </b><br/>
<img src="https://i.imgur.com/6qAyuCc.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* The text is displayed with bold and italic formatting (頁面會顯示粗體與斜體文字)<br/>
* The DVWA reaction means that it fails to properly sanitize inputs and encode outputs, which lets browsers interpret HTML tags directly. <br/>This creates a risk of cross-site scripting (XSS).<br/>(DVWA 的反應意味著它未能正確過濾輸入和編碼輸出，導致瀏覽器直接解釋 HTML 標籤，從而存在跨站腳本 (XSS) 風險)</b>
<br/>
<br />
<b>Task 3: Run ClamAV Scan<br/>(執行 ClamAV 掃描) </b><br/>
<img src="https://i.imgur.com/ROB9bQr.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* An alert box immediately shows the session cookie, but even if you leave the page and return again, the script will still be valid. <br/>(警告框會立即顯示會話 cookie，但即使離開該頁面並再次返回，腳本仍然有效)</b>
<br/>
<br />
<b>Task 4: Schedule Automatic Scans with Crontab<br/>(使用 Crontab 設定排程掃描) </b><br/>
<img src="https://i.imgur.com/PxD35yx.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Inject the same code and try to revisit the page. <br/>(注入相同的程式碼並嘗試重新訪問該頁面)<br/>
* An alert box immediately shows the session cookie, but if you leave the page and return again, the script will no longer be valid. <br/>(警告框會立即顯示會話 cookie，但若離開該頁面並再次返回，腳本將不再有效)</b>
<br/>


---------

