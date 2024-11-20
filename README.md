#  Recipe Bot

An interactive chatbot crafted to deliver personalized culinary suggestions, guiding users through a diverse collection of curated recipes.

## Functions
- **Tailored Recommendations:** Suggests recipes based on individual preferences.
- **Recipe Discovery:** Displays related recipe options to expand choices.
- **Live Chat Functionality:** Built with Socket.io for dynamic, real-time interactions.

## Tech Stack
- **Frontend:** Next.js
- **Backend:** Flask (Main Server), Node.js (Socket.io microservice)
- **Database:** MongoDB (Chat Storage)
- **Vector Database:** Qdrant

## Libraries & Tools
- **LangChain & OpenAI:** Powers advanced recommendation logic.
- **Qdrant:** Efficiently handles vector data for quick and precise recipe matches.

## Setup & Installation

Follow these steps to set up and run the Foodie Bot locally in your system :

### Steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/Anandhupa1/GENAI-MAIN-PROJECT.git
    ```

2. **Navigate to the Client Directory:**
    ```bash
    cd GENAI-MAIN-PROJECT/client
    ```

3. **Install Dependencies:**
    ```bash
    npm install
    ```

4. **Run the Frontend:**
    ```bash
    npm run dev
    ```

This will start the Next.js application on the default port, usually `http://localhost:3000`. Open this URL in your browser to view and interact with the application.

<img src="client/gifs/foodieGif1.gif" width="100%" alt="Foodie Bot GIF">


