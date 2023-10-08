# Membership Inference Attack 

This project explored the membership inference attack and demonstrated its effectiveness in real-world examples. The investigation highlighted how a machine learning model's workflow can be used for membership inference, determining if a specific data point was part of the model's training dataset.

To execute a membership inference attack, shadow models were created to classify data as either members or non-members. These shadow models were then trained on the attributes of member and non-member data. Subsequently, they were used to infer whether a given data point was part of the target model's training dataset. Seven different shadow models were implemented and shown to be effective in executing the membership inference attack.

However, limitations were identified, including the need for partial access to the training data and the assumption that the target model's predictions are deterministic. Further research areas were also highlighted, such as using advanced machine learning models and algorithms to enhance attack accuracy, exploring defenses against membership inference attacks, and assessing the attack's effectiveness in domains beyond image classification.

Overall, this work emphasizes the importance of safeguarding machine learning models against membership inference attacks, especially in sensitive domains like healthcare or finance, where revealing membership information can lead to severe consequences. The hope is that this investigation and the implementation of membership inference attacks and shadow models will raise awareness about this type of attack and inspire further research to develop robust defenses against it.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Provide a brief overview of your project. Explain what it does, why it exists, and what problems it solves. Use this section to give readers a high-level understanding of your project.

## Getting Started

Provide instructions on how to get started with your project. Include information about any prerequisites and installation steps.

### Prerequisites

List any software or tools that users need to have installed before they can use your project.

### Installation

Provide step-by-step instructions on how to install your project. You can use code blocks to show commands.

```shell
# Example installation steps
git clone https://github.com/yourusername/yourproject.git
cd yourproject
npm install
