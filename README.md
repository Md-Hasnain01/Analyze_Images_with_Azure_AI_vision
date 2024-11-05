# Analyze_Images_with_Azure_AI_vision

## Project Description

This project utilizes Microsoft Azure's Computer Vision API to analyze images. The application performs tasks such as language detection, object detection, and background removal. It leverages the Azure AI Vision client to extract valuable insights from images, including captions, tags, and detected objects.

## Features

- Analyze images to extract captions, tags, and detected objects.
- Draw bounding boxes around detected objects and people.
- Remove backgrounds from images using Azure's segmentation capabilities.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine.
- An Azure account with access to the Computer Vision API.
- Required Python packages installed (see Installation section).

## Example Output

Original Image

![street](https://github.com/user-attachments/assets/c688a57c-0c19-4ee9-aa25-3df94f0642a5)

Detected Image

![street detected](https://github.com/user-attachments/assets/2d994c00-c6dc-43dc-8eee-eb67ed25564a)

Street Background Removing

![street background remove](https://github.com/user-attachments/assets/91d94f91-648e-4f96-b3a5-da9ec66ab94f)

Forge Matting

![forge matting](https://github.com/user-attachments/assets/61893d89-95b9-4339-973a-1f037ffdef77)

## Setup

## Create a `.env`

Set up your environment variables. Create a `.env` file in the root directory of the project and add your Azure credentials:

AI_SERVICE_ENDPOINT= `<your_azure_endpoint>`

AI_SERVICE_KEY= `<your_azure_key>`

## Acknowledgments

Microsoft Azure for providing the Computer Vision API.
Pillow for image processing.
Matplotlib for visualizing the results.
