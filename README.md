# Cypher

Welcome to Cypher, a powerful and versatile tool for data encryption and decryption using advanced cryptography. This project offers a secure and efficient solution for safeguarding sensitive information, making it an ideal choice for applications where data privacy is paramount.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Examples](#examples)
- [License](#license)

## Introduction

In today's digital age, ensuring the confidentiality and integrity of sensitive data is of utmost importance. Cypher addresses this concern by employing an innovative  cryptographic technique that enhances security while maintaining practicality.

With its intuitive command-line interface and robust encryption algorithms, Cypher simplifies the process of encrypting and decrypting text, ensuring that only authorized individuals can access the original content.

## Features

- Command-line interface for easy interaction.
- Efficient encryption and decryption algorithms to ensure quick and secure data protection.
- Key-based cyphers for managing encryption keys in a secure manner.
- Capability to encrypt text with ASCII values ranging from 32 to 126, including tab and new line characters. This ensures compatibility with a wide range of textual data types.

Whether you're securing personal communications, protecting confidential business data, or conducting research in cryptography, Cypher empowers you with the tools you need to keep your information safe and confidential.

## Getting Started

To get started with Cypher just download the executable file cypher, now you can quickly encrypt and decrypt data using the intuitive command-line interface.

### Prerequisites

linux operating system

## Usage

./orion -[flag] -k [keyword] < [input_file] > [output_file]
- flag: e for encryption and d for decription
- keyword: can contain only chars between a-z, A-Z, 0-9

## Examples

- ./orion -e -k Keyword123 < input > encrypted
- ./orion -d -k Keyword123 < encrypted > decrypted
