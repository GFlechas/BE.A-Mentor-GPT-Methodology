# BE.AMentor - GPT Methodology Toolkit

<div align="center">
    <img src="beamentor_logo.png" alt="BE.AMentor Logo" />
</div>

Welcome to **BE.AMentor - GPT Methodology Toolkit**, an open-source repository outling the process you can use to develop a Building Energy Modeling/Analysis focused custom GPT to answer questions about standards, code compliance, and modeling practices. Developing a custom  

This repo includes the configuration information you can use to initialize a custom Building Energy Analysis mentor, however to do so requires a ChatGPT Plus account. However,project aims to aid building energy modeling and HVAC practitioners by providing insightful answers to questions about ASHRAE standards, guidelines, and various building energy modeling tools such as OpenStudio, EnergyPlus, and DesignBuilder.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Create your Own Mentor](<#create-your-own-mentor>)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

**BE.AMentor** leverages the power of OpenAI custom GPTs to assist practitioners in the building energy modeling field. By incorporating quantitative data from open-source datasets, including DOE's prototype buildings, our custom GPT provides accurate and contextually relevant responses.

## Features

- **Expert Guidance:** Get reliable answers to questions about ASHRAE standards and guidelines.
- **Modeling Support:** Assistance with tools like OpenStudio, EnergyPlus, and DesignBuilder.
- **Data-Driven Insights:** Incorporates data from DOE's prototype buildings and other open-source datasets.
- **Interactive Responses:** Engage with a dynamic and responsive custom GPT designed for energy analysis.

## Demo

You can use our demo **BE.AMentor Custom GPT** at _______. Using the demo Custom GPT requires you to login with an OpenAI account (free or paid), however, you do **not** need a ChatGPT Plus subscription to use an already made custom GPT. You just need an email address to register for a free ChatGPT account and after doing so you can interact with our **BE.AMentor Custom GPT** demo.

## Create your Own Mentor

There are two ways to develop your own Building Energy Analysis GPT mentor: through [ChatGPT's Custom GPT Builder](<https://chatgpt.com/gpts/editor>) in the web interface, or by interfacing with ChatGPT through OpenAI's API.

### Through the Web Interface

1. Sign in to your [OpenAI ChatGPT Account](<https://chat.openai.com/auth/login?sso>)

1. Navigate to the [New GPTs editor](<https://chatgpt.com/gpts/editor>)

1. Click *Explore GPTs*

### Through the API

You can create your own custom Building Energy Analysis GPT mentor in two ways. You can use the [beamentor_GPT_foundation.py](beamentor_GPT_foundation.py) script to interface with ChatGPT through OpenAI's API interface.

## Installation

To get started with **BE.AMentor**, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/BE.AMentor.git
    ```
2. Navigate to the project directory:
    ```bash
    cd BE.AMentor
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use **BE.AMentor**, simply run the main script and start interacting with the custom GPT:

```bash
python main.py
```

You can ask questions about building energy modeling, ASHRAE standards, and more. Here are a few examples:

- *"What are the key ASHRAE guidelines for HVAC systems?"*
- *"How do I model a commercial building in EnergyPlus?"*
- *"What are the energy savings potential for using DOE's prototype buildings data?"*

## Contributing

We welcome contributions to **BE.AMentor**! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add your message"
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature
    ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

IBPSA USA and the SimBuild Conference Organizers have our gratitude for their support of novice and seasoned practioners alike in the Building Energy Modeling community. And thanks to our fellow participants of the HackSimBuild 2024 competition for their valuable input and feedback on this project.

---

**BE.AMentor** - Your Guide to Building Energy Analysis

---
