#  Virus Scanning Setup and Automation using ClamAV in Linux
在 Linux 系統中使用 ClamAV 進行病毒掃描與自動化設定

<h2>Outline 簡介</h2>

As part of the Week's "Securing Networks" lab, we completed a practical exercise involving the installation, configuration, testing, and automation of ClamAV, a widely used open-source antivirus solution for Linux systems.


作為本週「Securing Networks」實作的一部分，我們完成了有關安裝、設定、測試以及自動化 ClamAV 防毒系統的練習。ClamAV 是 Linux 系統上廣泛使用的開源防毒解決方案。

<h2>Key Learning Outcomes 主要學習成果</h2>

- <b>Installed ClamAV and its related graphical and mail scanning tools via Synaptic Package Manager. (使用 Synaptic 套件管理器安裝 ClamAV 及其相關圖形介面與郵件掃描工具)</b>

- <b>Configured system PATH and modified the .profile file to ensure command availability across sessions. (設定系統 PATH 並修改 .profile 檔案，以確保命令在每次啟動虛擬機時皆可用)</b>

- <b>Downloaded the EICAR test virus file to validate ClamAV's detection capabilities in a controlled, safe environment. (下載 EICAR 測試病毒檔案，以在受控安全的環境中驗證 ClamAV 的偵測能力)</b>

- <b>Performed manual virus scans using ClamAV to understand detection logs and scanning behavior. (使用 ClamAV 進行手動病毒掃描，以瞭解其偵測日誌與掃描行為)</b>

- <b>Set up an automated daily virus scan on the home directory via crontab (scheduled at 1:35 AM).(透過 crontab 排程功能，設定每天凌晨 1:35 自動掃描使用者主目錄)</b>

<h2>Security and Administrative Implications 資安與系統管理層面涵義</h2>

This task introduced us to real-world cybersecurity practices and automated system maintenance. We learned how to implement scheduled protection routines and handle potential threats using CLI tools, which are essential in any professional IT environment.

這項練習讓我們接觸到實際資安操作與系統維護自動化的流程。我們學會如何實作排程式防護機制，並透過指令列工具處理潛在威脅，這些都是專業 IT 環境中不可或缺的技能。

<h2>Tools and Concepts Covered 涵蓋工具與概念</h2>

| Aspect (面向)       | Learning content and purpose (學習內容與目的)                           |
| -------- | --------------------------------- |
| System management (系統管理)     | Use Synaptic, modify `.profile`, set PATH (使用 Synaptic、修改 `.profile`、設定 PATH) |
| Antivirus practice (防毒實務)     | Install ClamAV, antivirus test and manual scan (安裝 ClamAV、防毒測試與手動掃描)               |
| Information security test (資安測試)     | Use a legitimate virtual virus (EICAR) to test the scanning effect (使用合法的虛擬病毒 (EICAR) 測試掃描效果)          |
| Automated job management (自動化作業管理)  | Set up Cron tasks to perform scans regularly (設定 Cron 任務，定期執行掃描)                 |
| Information security practical thinking (資訊安全實務思維) | Establish a general defense cycle for antivirus systems and strengthen operation and scheduling capabilities(建立防毒系統的一般防禦週期，強化操作與排程能力)           |
