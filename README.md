# AI Image Generator with DALL·E 3

Welcome to the AI Image Generator, a dynamic React web application that leverages the OpenAI DALL·E 3 model to transform your text prompts into stunning images. Dive into the world of AI-driven art creation with ease and precision.

![DALL·E 3 Logo](./public/Task%208.png)

## Live Demo

Check out the live demo [here](https://main--bytewisetask8.netlify.app/).

## Key Features

- **Text Prompt Image Generation:** Convert your text descriptions into visual art.
- **Customizable Styles and Moods:** Select predefined options to shape the artistic output.
- **Image Download:** Save your generated images effortlessly.
- **Responsive Design:** Seamlessly access on various devices, from desktops to mobiles.

## Prerequisites

Ensure you have the following before getting started:

- Node.js installed on your machine.
- An API key from OpenAI.

## Installation Guide

Follow these steps to set up the AI Image Generator:

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/MuhammadZawar11681/Image-Generator-OpenAi-Api.git

   ```

2. Navigate to the project directory:
   ```
   cd Image-Generator-OpenAi-Api
   ```
3. Install the required dependencies:
   ```
   npm install
   ```
4. Create a `.env` file in the root of the project and add your OpenAI API key:
   ```
   REACT_APP_OPENAI_API_KEY=your_openai_api_key
   ```

## Running the Application

To run the application in development mode, use the following command:

```
npm start
```

This will start the React app and open it in your default web browser.

## Usage

- Choose between the "Manual Prompt" or "Predefined Options" tab.
- Input a description for the image you wish to generate.
- Click "Generate" to request an image from OpenAI's API.
- Once the image is generated, it will be displayed with an option to download.
