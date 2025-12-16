Neural Network–Based Encryption & Decryption Tool

SecureChat is a demonstration of neural network–based text encryption and decryption designed for secure message communication.
This project leverages artificial neural networks (ANNs) using TensorFlow to transform plain text messages into encrypted cipher text and securely decrypt them at the receiver’s end.

📌 Developed as a B.Tech Final Year Project
Technocrats Institute of Technology, Bhopal

🚀 Project Overview

Traditional encryption techniques rely on predefined mathematical algorithms. SecureChat explores an AI-driven approach to encryption, where a multi-layer neural network learns complex transformations to encode and decode messages securely.

The system behaves like a secure chatbot, allowing users to:

Enter a private message

Encrypt it using a neural encryption model

Decrypt it accurately only with the correct neural configuration and key

This project demonstrates how neural networks can be applied in cryptography for secure communication.

🧠 How SecureChat Works

SecureChat uses a 7-layer auto-associative neural network combined with a randomly generated key matrix.

🔑 Encryption Process

User enters a plain text message

Text is converted into numerical vectors

A randomly generated key matrix is applied

The data passes through a 7-layer neural network

Multiple transformations using:

Matrix multiplication

Weighted sums

Activation functions

Output is an encrypted cipher text

🔓 Decryption Process

Encrypted message is fed into the same neural model

Reverse transformations occur

Original message is reconstructed accurately

📌 Without the trained neural model and correct key matrix, decryption is not possible

🏗️ System Architecture

Input Layer – Text vector representation

Hidden Layers – Neural transformations (7 layers)

Activation Functions – Non-linear encryption strength

Key Matrix – Adds randomness and security

Output Layer – Encrypted or decrypted message

This architecture ensures:

High diffusion

Non-linear encryption

Resistance to pattern recognition

💡 Features

Neural network–based encryption & decryption

Secure chatbot-style message exchange

Auto-associative ANN model

Random key matrix generation

TensorFlow-powered implementation

Educational and research-oriented cryptography project

🛠️ Technologies Used

Python

TensorFlow

NumPy

Artificial Neural Networks (ANN)

Matrix Operations

Machine Learning Concepts
