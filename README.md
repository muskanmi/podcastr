# Podcastr Application

![image](https://github.com/muskanmi/podcastr/assets/54322853/4a135a93-80e1-4dfa-9ab4-c50b0f968ad3)

[Podcastr Live Website (https://podcastr-green.vercel.app)](https://podcastr-green.vercel.app/)

Welcome to Podcastr, an AI-powered Software-as-a-Service (SaaS) application designed to revolutionize podcast creation and management. This application leverages cutting-edge AI technologies to provide features such as text-to-multiple-voices functionality and AI-generated images, all built using Next.js 14 and Convex.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Usage](#usage)
    - [Text-to-Voice](#text-to-voice)
    - [AI-Generated Images](#ai-generated-images)
5. [Configuration](#configuration)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction

Podcastr is designed for podcast creators who want to enhance their production quality with AI. By providing a platform where text can be converted into multiple voices and custom images can be generated for each episode, Podcastr simplifies the process of creating professional-grade podcasts.

## Features

- **Text-to-Multiple-Voices Functionality**: Convert written content into speech using a variety of AI-generated voices, giving each character or segment a unique sound.
- **AI-Generated Images**: Automatically generate custom images for podcast episodes, improving visual appeal and audience engagement.
- **Built with Next.js 14**: Leveraging the latest features of Next.js for optimal performance and scalability.
- **Powered by Convex**: Utilizing Convex for efficient and secure data management and AI model integration.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v16.0.0 or later)
- npm or yarn
- Git

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/podcastr.git
    cd podcastr
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```
    or
    ```bash
    yarn install
    ```

3. **Set up environment variables**:
    Create a `.env.local` file in the root directory and add your configuration settings (API keys, database URLs, etc.).

    Example:
    ```env
    NEXT_PUBLIC_API_KEY=yourapikey
    CONVEX_API_URL=https://yourconvexinstance.com
    ```

4. **Run the development server**:
    ```bash
    npm run dev
    ```
    or
    ```bash
    yarn dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

### Text-to-Voice

1. Navigate to the Text-to-Voice section in the application.
2. Enter your text into the provided input field.
3. Select the desired voices for different parts of the text.
4. Click "Generate" to create the audio file.
5. Listen to or download the generated audio.

### AI-Generated Images

1. Go to the AI-Generated Images section.
2. Enter the description or keywords for the image you need.
3. Click "Generate Image" to create a custom image for your podcast episode.
4. View and download the generated image.

## Configuration

Additional configuration options can be set in the `.env.local` file or within the application settings. Ensure you have all required API keys and service URLs configured properly.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

Please ensure your code adheres to the existing code style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For support, please contact the development team at support@podcastr.ai or create an issue in the GitHub repository.

---

Thank you for using Podcastr! We hope our application helps you create amazing podcasts with ease.
