# Outfit Idea Generator

## Overview

The Outfit Idea Generator is an innovative application designed to help users curate stylish and personalized outfit suggestions using their existing wardrobe. By combining user feedback with the advanced capabilities of OpenAI's DALL-E, this tool offers refined and creative outfit ideas tailored to individual preferences.

## Features

- **Wardrobe Input**: Users can effortlessly upload pictures of their clothing items.
- **Outfit Suggestions**: The application provides initial outfit ideas based on the uploaded wardrobe images.
- **User Feedback Loop**: Users can approve or reject outfit suggestions to refine their preferences:
  - **Yes**: Adds the outfit to a favorites list.
  - **No**: Discards the outfit.
- **AI Enhancement**: Leveraging the favorites list, the tool utilizes DALL-E from OpenAI to generate new, creative outfit ideas.
- **Continuous Improvement**: The iterative process continues, allowing users to refine their wardrobe choices until they find the perfect DALL-E generated outfit.

## How It Works

1. **Upload Wardrobe**: Users begin by uploading pictures of their clothing items.
2. **Initial Suggestions**: The application generates initial outfit ideas from the uploaded wardrobe.
3. **User Feedback**: Users review and provide feedback on the suggested outfits:
    - **Yes**: Adds the outfit to the favorites list.
    - **No**: Discards the outfit.
4. **AI Generation**: The favorites list is sent to DALL-E, which then generates new outfit ideas based on the user's refined preferences.
5. **Final Selection**: The process repeats until the user approves a DALL-E generated outfit, ensuring a highly personalized result.

## Getting Started

### Prerequisites

- Node.js
- Python
- OpenAI API key

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/spencerwozniak/outfit-idea-generator.git
    cd outfit-idea-generator
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory and add your OpenAI API key:
    ```plaintext
    OPENAI_API_KEY=your_openai_api_key
    ```

4. **Run the application**:
    ```bash
    npm start
    ```

### Usage

1. **Upload your wardrobe**: Navigate to the upload section and add pictures of your clothes.
2. **Review initial suggestions**: Approve or reject the initial outfit ideas.
3. **AI-generated outfits**: Review and approve or reject the outfits generated by DALL-E.
4. **Enjoy your personalized outfit**: Once satisfied with an outfit, save and enjoy your new look!

## Contributing

We welcome contributions to enhance the Outfit Idea Generator! To contribute, follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make your changes**.
4. **Commit your changes**:
    ```bash
    git commit -m 'Add some feature'
    ```
5. **Push to the branch**:
    ```bash
    git push origin feature/your-feature-name
    ```
6. **Create a pull request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://openai.com/) for their incredible DALL-E API.
- [Node.js](https://nodejs.org/) and [Python](https://www.python.org/) for the development environment.
