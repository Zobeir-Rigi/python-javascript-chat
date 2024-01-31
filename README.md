Hosted our chat backend in a ChatEngine.io project.
https://chatengine.io/ 

# Real-Time Chat App

Real-time chat application using FastAPI (Python) on the backend and React on the frontend.

## Features

- Real-time chat with file attachment
- Responsive design for mobile and desktop

## Usage

1. **Run the backend server:**

    ```bash
    uvicorn main:app --reload --port 3001
    ```

2. **Connecting to Chat Engine:**
   
   - Create an account on [Chat Engine](https://chatengine.io/).
   - Obtain a free project ID and private key.

3. **Run the frontend:**

    ```bash
    # Navigate to the project directory
    cd frontend
    
    # Install dependencies
    npm install   # or yarn install
    
    # Start the frontend
    npm start   # or yarn start
    ```
## About

- Built with FastAPI on the backend and React on the frontend.
- Focus on Python server-side development.
- Attach files to your messages.
- Responsive for both mobile and desktop.

## Run Server

```bash
uvicorn main:app --reload --port 3001

Requirements
Ensure all dependencies are installed by running:
pip install -r requirements.txt
