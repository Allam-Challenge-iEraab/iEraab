# **iEraab**

## **Project description**
This application provides a web-based API service for Arabic grammatical analysis, using FastAPI to create a server with an HTTP API that integrates with a model for natural language processing (NLP) of Arabic grammar. The API is designed to run locally and be accessible publicly via ngrok. Additionally, a web-based frontend is included to enable users to interact with the API and receive grammatical analysis of Arabic text input.


## **Code organization**

* **Imports and Configuration** Imports necessary libraries and sets up logging.
* **FastAPI Setup and CORS Configuration** Sets up the FastAPI app, applies nest_asyncio to avoid blocking issues with asynchronous operations in Jupyter, and configures CORS.
* **API Route Definitions** Defines the / route for a welcome message and the /chat route to accept user input and return the grammatical analysis.
* **Server and ngrok Configuration** Configures the server to run locally with uvicorn and expose it publicly with ngrok.
* **Frontend for User Interaction** Builds a simple HTML frontend to interact with the API in a browser.








