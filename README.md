# AI_Style_sheet 🎨🤖
An AI-powered tool to help artists refine their visual work by giving feedback based on style similarity.

## 📌 Overview
As part of my thesis, I developed AI_Style_sheet — a tool designed to assist artists and visual creatives by offering automatic evaluations of their images. The system compares input images to a defined visual style and provides quantitative ratings in several aesthetic categories, acting as a kind of AI style guide or stylesheet.

This project explores how AI can bridge the gap between artistic intuition and machine-driven assessment, supporting the creative process with insightful feedback.

## 🧠 What It Does
The AI model takes in an image and outputs ratings in the following categories:

Style Look

Props & Style Consistency

Color Grading

Scene Mood

These scores help artists understand how closely their image matches a reference style or concept, which can be particularly useful in film, game development, concept art, and branding work.

## ⚙️ How It Works
Data Preparation

A dataset of images labeled with stylistic attributes is used to train the model.

Model Architecture

A custom CNN (Convolutional Neural Network) extracts features from input images.

A lightweight MLP (Multi-Layer Perceptron) head predicts the scores.

Training

Uses cosine similarity and MSE losses for accurate style representation.

Evaluation

Artists can upload an image, and the AI returns a 4-category style rating.
