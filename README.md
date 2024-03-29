#  FIR Chatbot

Welcome to the FIR (Fast Information Retrieval) Chatbot, a tool designed to provide quick and accurate medical information. Utilizing advanced language models and vector stores, this guide will assist you in setting up and using the FIR Chatbot effectively.

## Table of Contents

- [👋 Introduction](#fir-chatbot)
- [🔍 Prerequisites](#prerequisites)
- [⚙️ Installation](#installation)
- [🚀 Getting Started](#getting-started)
- [💡 Usage](#usage)
- [🤝 Contributing](#contributing)
- [📝 License](#license)

## 🔍 Prerequisites

Before you start using the FIR Chatbot, ensure that your system meets the following requirements:

- Python 3.6 or higher
- Required Python packages (install via pip):
    - langchain
    - chainlit
    - sentence-transformers
    - faiss
    - PyPDF2 (for loading PDF documents)

## ⚙️ Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/your-username/fir-chatbot.git
    cd fir-chatbot
    ```

2. Optionally, set up a Python virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the necessary Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Refer to the Langchain documentation for detailed instructions.

5. Configure paths and settings in your project, including the `DB_FAISS_PATH` variable.

## 🚀 Getting Started

To start using the FIR Chatbot:

1. Set up your environment and install required packages as instructed in the Installation section.

2. Customize your project by updating configurations in the code.

3. Prepare language models and data according to the Langchain documentation.

4. Start the bot by running the provided Python script or integrating it into your application.

## 💡 Usage

Use the FIR Chatbot for retrieving medical information:

1. Launch the bot by running your application or using the provided script.

2. Send a medical query to the bot.

3. Receive a response based on available information in its database.

4. If sources are found, they will accompany the answer.

5. Customize the bot to return specific information based on the query and context.

## 🤝 Contributing

Contributions to the FIR Chatbot are welcome! Follow these steps:

1. Fork the repository to your GitHub account.

2. Create a new branch for your feature or bug fix.

3. Implement changes and ensure passing tests.

4. Submit a pull request to the main repository, detailing your modifications.

5. Your pull request will undergo review and, if approved, be merged into the main codebase.

