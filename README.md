# AI Drawing Calculator and Problem Solver (Backend)

This is the backend service for the AI Drawing Calculator and Problem Solver. It processes images of drawn mathematical expressions and returns solutions using AI models.

Frontend: https://github.com/krmahi/AI-Drawing-Calculator-and-Problem-Solver

## 🌐 Live API

Access the live API here: [ai-drawing-calculator-and-problem-solver-backend.vercel.app](https://ai-drawing-calculator-and-problem-solver-backend.vercel.app)

## 🛠️ Features

- **Image Processing:** Accepts images of handwritten mathematical expressions.
- **AI-Powered Solving:** Utilizes AI models to interpret and solve the expressions.
- **API Endpoints:** Provides RESTful API endpoints for frontend integration.

## 🧰 Technologies Used

- **Python** for backend development
- **FastAPI** for building the API
- **Vercel** for deployment

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/krmahi/AI-Drawing-Calculator-and-Problem-Solver-Backend.git
   cd AI-Drawing-Calculator-and-Problem-Solver-Backend
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   uvicorn main:app --reload
   ```

   The API will be available at `http://localhost:8000`.

## 📁 Project Structure

- `apps/calculator/`: Contains the main application logic
- `main.py`: Entry point of the application
- `schema.py`: Defines data models and schemas
- `constants.py`: Application constants
- `requirements.txt`: Python dependencies
- `vercel.json`: Vercel deployment configuration

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## 📄 License

This project is licensed under the [Apache 2.0 License](https://github.com/krmahi/AI-Drawing-Calculator-and-Problem-Solver-Backend/blob/main/LICENSE).

## 📬 Contact

For questions or feedback, please contact Mahesh Kumar at [mahesh.kr.2277@gmail.com](mailto:mahesh.kr.2277@gmailcom).
