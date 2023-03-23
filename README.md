# ChatGPT Project

This project consists of two main components: `client-chatgpt` and `server-chatgpt`.

## client-chatgpt

This is the client-side application for the ChatGPT project.

### Getting started

To set up and run the client, follow these steps:

1. Change to the `client-chatgpt` directory:

cd client-chatgpt


2. Install the required packages:

npm install


3. Run the development server:

npm run dev


The client-side application should now be running and accessible in your browser.

## server-chatgpt

This is the server-side application for the ChatGPT project.

### Getting started

To set up and run the server, follow these steps:

1. Change to the `server-chatgpt` directory:

cd server-chatgpt


2. Install all required Python packages. It's recommended to use a virtual environment:

python -m venv venv
source venv/bin/activate # On Windows, use venv\Scripts\activate
pip install -r requirements.txt

3. Run the FastAPI server using uvicorn:

`uvicorn main:app --host 0.0.0.0 --port 3080
`

