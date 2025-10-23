# n8n Course Example Workflows

This repository contains the example workflows for the [NTU CSIE Course: n8n × AI Agents: 自動化程式入門](https://train.csie.ntu.edu.tw/school/courses/course.php?id=5823).

Each JSON file in the `Workflows` directory represents a unique n8n workflow demonstrated during the course.

## Prerequisites

Before you begin, please ensure you have an n8n server instance running. These workflows were created with n8n version `1.106.3` and are best compatible with that version or newer.

## How to Use

1. **Download the Workflows**: Clone or download this repository to your local machine.
2. **Import into n8n**: Open your n8n canvas and import the desired `.json` files from the `Workflows` directory. You can import workflows one by one or select multiple to add them to your n8n instance.

    ```bash
    # Import all the workflows in the `Workflows` directory
    n8n import:workflow --separate --input=./Workflows
    ```