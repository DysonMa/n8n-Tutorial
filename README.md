# n8n Course Example Workflows

This repository contains the example workflows for the [NTU CSIE Course: n8n × AI Agents: 自動化程式入門](https://train.csie.ntu.edu.tw/school/courses/course.php?id=5823).

Each JSON file in the `Workflows` directory represents a unique n8n workflow demonstrated during the course.

## Prerequisites

Before you begin, please ensure you have an n8n server instance running. These workflows were created with n8n version `1.106.3` and are best compatible with that version or newer.

## How to Use

1. **Download the Workflows**: You can either **clone this repository** to your local machine or download the tar.gz archive from the [Release](https://github.com/DysonMa/n8n-Tutorial/releases) page.

    Refer to the ID–name mapping below.

    ```json
    {
      "l753I0uUdDXCmB3X": "2-1. 本地檔案讀寫",
      "HfRdilhurezW921G": "2-2. 邏輯控制 (if, switch)",
      "7m2WF1sBHPtvdSl3": "2-3. Code Node",
      "O8p0WDgx3OwqPuaM": "2-4. 電腦維修 Google Forms",
      "uwJ2cxjiv3xa8Wsb": "2-5. Google Sheets 操作",
      "zEIjkGcu2HvSRMjj": "2-6. 台股資料上傳Google Drive",
      "jWoBETY8INg5umvm": "2-7. 單日漲幅前十多股票",
      "i5LxmZzDaNcx8C66": "2-8. 完整台股資料串接",
      "l26WV2Pg98SIyr8i": "2-9. 單日漲幅前十多股票前月表現",
      "LE6kndGwgeYSWD3i": "2-10. RSS商周文章訂閱",
      "iEMaIxKGUAD7gIJW": "2-11. 錯誤例外處理",
      "tN1LnXrBMs8hefqz": "2-12. 台灣銀行匯率爬蟲",
      "2fsP25FHVR9CpLZz": "2-13. Error Trigger Workflow",
      "48m5Jvj4AXClOXFz": "4-1. RSS商周文章訂閱寫入Notion",
      "McJfrYdTMISzsjCR": "4-2. Ollama總結Notion文章",
      "HIOHEv37RDK1HEVp": "4-3. Groq總結Notion文章",
      "XH9B0jqbrXJ7SIw1": "4-4. Groq文字轉語音",
      "VZ6lQRHkqiVcDaFw": "4-5. 與AI模型對話",
      "qAQV7olLC9qFwMUG": "4-6. 打造LINE聊天機器人",
      "bQfzSAphmcljgCSV": "4-7. AI Agent x Gemini 代理人",
      "DA1RAWzvv8WCsoaR": "4-8. 當日匯率查詢",
      "RoRcKHHXO4gqQJg8": "4-9. AI Agent x Gemini 代理人 x LINE 聊天機器人",
      "hW5rtsnGmKC5s7Jn": "Edit Field介紹"
    }
    ```
   
3. **Import into n8n**: Open your n8n canvas and import the desired `.json` files from the `Workflows` directory. You can import workflows one by one or select multiple to add them to your n8n instance.

    ```bash
    # Import all the workflows in the `Workflows` directory
    n8n import:workflow --separate --input=./Workflows
    ```
