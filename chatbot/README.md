#  Chatbot

## Overview
The ** Chatbot** is an intelligent assistant designed to answer "how-to" questions related to four Customer Data Platforms (CDPs):


The chatbot fetches relevant information from the official documentation of these platforms and provides step-by-step guidance for performing tasks and achieving specific outcomes within each .

## Features
- **Conversational AI**: Uses Google AI's **PaLM API** to process and generate responses.
- **-Specific Guidance**: Extracts and provides precise information from official documentation.
- **React-Based UI**: A clean and interactive interface built with **React.js**.
- **Context-Aware Responses**: Understands the intent behind user queries for accurate guidance.
- **Fast & Scalable**: Optimized for performance and scalability using modern frontend development practices.
- **Dynamic Search**: Retrieves documentation content in real-time.

## Tech Stack
### Frontend:
- **React.js**: For building the user interface.
- **Tailwind CSS**: For styling the chatbot UI.
- **React Query / Axios**: For API calls and data fetching.

### Backend & AI:
- **Google AI's PaLM API**: For intelligent response generation.

## Installation & Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/gautamsharma5543/ChatBot/tree/main/chatbot
   cd cdp-chatbot
   ```
2. **Install Dependencies:**
   ```sh
   npm install
   ```
3. **Set Up Google AI PaLM API:**
   - Obtain an API key from Google Cloud.
   - Create a `.env` file and add:
     ```env
     REACT_APP_PALM_API_KEY=your_api_key_here
     ```
4. **Run the Development Server:**
   ```sh
   npm run dev
   ```

## Usage
- Enter a question related to Segment, mParticle, Lytics, or Zeotap.
- The chatbot processes the query using the **PaLM API** and provides relevant documentation insights.
- Follow step-by-step instructions provided by the bot.

## Future Enhancements
- **Integration with  APIs** for real-time insights.
- **User Authentication** for personalized recommendations.
- **Multilingual Support** for broader accessibility.

## License
This project is licensed under the MIT License.

---
Developed with ❤️ using **React.js** & **Google AI PaLM API**.


