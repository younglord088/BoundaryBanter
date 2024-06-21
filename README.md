# Boundary Banter

Boundary Banter is a project focused on automating the generation of cricket news from live text commentary using advanced Natural Language Processing (NLP) techniques. This project aims to transform live sports commentary into concise news summaries, enhancing user experience and enabling real-time information dissemination.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Sporting events, especially cricket, attract a global audience. Many enthusiasts prefer reading news articles over watching live streams due to time constraints. This project addresses the need for rapid and automated news production post-match by converting live commentary into news articles using NLP.

## Features

1. **Enhanced User Experience**: Provides timely and concise summaries of cricket matches.
2. **Automation in Journalism**: Reduces the manual effort required for drafting reports.
3. **Personalized Content Delivery**: Allows customization of news based on user preferences.
4. **Real-time Information Dissemination**: Facilitates rapid sharing of match updates and analyses.
5. **Research Advancements**: Contributes to advancements in NLP and machine learning research.
6. **Commercial Applications**: Techniques can be applied across various domains like finance, healthcare, and e-commerce.
7. **Ethical Considerations**: Ensures fairness, accuracy, and transparency in automated news generation.

## Dataset

Data for this project is collected from the ESPNCricinfo website. The dataset, named CricSum, is available for further research and development. The dataset contains live text commentaries of cricket matches, which are used for training and evaluating the model.

## Model

The project utilizes the pre-trained BART model for abstractive text summarization. The model is trained in a template2template manner to generate coherent and fluent summaries. The performance of the model is evaluated using ROUGE scores:
- **ROUGE 1**: High
- **ROUGE L**: High
- **ROUGE 2**: Requires improvement

## Installation

To install and run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/younglord088/BoundaryBanter.git
    ```
2. Navigate to the project directory:
    ```bash
    cd BoundaryBanter
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. To process live commentary and generate summaries, run:
    ```bash
    python generate_summary.py --input live_commentary.txt --output summary.txt
    ```
2. For detailed usage and options, refer to the [documentation](docs/usage.md).

## Contributing

We welcome contributions from the community. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

For more details, please refer to our [contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, feedback, or collaboration, please contact:

- **Project Lead**: [Your Name](mailto:yashmpanjwani@gmail.com)
- **GitHub**: [Your GitHub Profile](https://github.com/younglord088)

I appreciate your interest and contributions to Boundary Banter!
