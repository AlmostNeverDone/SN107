#  Virus Scanning Setup and Automation using ClamAV in Linux
在 Linux 系統中使用 ClamAV 進行病毒掃描與自動化設定

<h2>Outline 簡介</h2>

This project demonstrates how to install, configure, and test the ClamAV antivirus software in a controlled Linux VM environment. The lab includes installing ClamAV with GUI tools, scanning files with the EICAR test virus, and configuring scheduled scans with Crontab.

本專案展示如何在 Linux VM 中安裝、設定並測試 ClamAV 防毒軟體，內容涵蓋透過圖形介面安裝 ClamAV、使用 EICAR 測試病毒檔進行掃描，以及利用 Crontab 安排排程掃描。

<h2>Key Learning Outcomes 主要學習成果</h2>

* Install and configure ClamAV with GUI support. (安裝並設定含圖形介面的 ClamAV)

* Use the EICAR test virus to validate ClamAV detection. (使用 EICAR 測試病毒驗證 ClamAV 偵測功能)

* Run manual virus scans and interpret results. (執行手動掃描並解讀結果)

* Automate regular scans using Crontab. (透過 Crontab 自動化排程掃描)

<h2>Security and Administrative Implications 資安與系統管理層面涵義</h2>

This task introduced us to real-world cybersecurity practices and automated system maintenance. We learned how to implement scheduled protection routines and handle potential threats using CLI tools, which are essential in any professional IT environment.

這項練習讓我們接觸到實際資安操作與系統維護自動化的流程。我們學會如何實作排程式防護機制，並透過指令列工具處理潛在威脅，這些都是專業 IT 環境中不可或缺的技能。

<h2></h2>

<h2>Tools and Concepts Covered 涵蓋工具與概念</h2>

| Aspect <br/>(面向)       | Learning content and purpose <br/>(學習內容與目的)                           |
| -------- | --------------------------------- |
| System management <br/>(系統管理)     | Use Synaptic, modify `.profile`, set PATH <br/>(使用 Synaptic、修改 `.profile`、設定 PATH) |
| Antivirus practice <br/>(防毒實務)     | Install ClamAV, antivirus test and manual scan <br/>(安裝 ClamAV、防毒測試與手動掃描)               |
| Information security test <br/>(資安測試)     | Use a legitimate virtual virus (EICAR) to test the scanning effect <br/>(使用合法的虛擬病毒 (EICAR) 測試掃描效果)          |
| Automated job management <br/>(自動化作業管理)  | Set up Cron tasks to perform scans regularly <br/>(設定 Cron 任務，定期執行掃描)                 |
| Information security practical thinking <br/>(資訊安全實務思維) | Establish a general defense cycle for antivirus systems and strengthen operation and scheduling capabilities<br/>(建立防毒系統的一般防禦週期，強化操作與排程能力)           |
