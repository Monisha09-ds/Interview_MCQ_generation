# AI-Powered Quiz Generation System

This project features an **AI-powered quiz generation system** that creates customized practice questions based on user input. Designed to assist learners and educators, the system leverages advanced natural language processing (NLP) models to dynamically generate quizzes tailored to specific topics, difficulty levels, and formats.

## Key Features

- **Customizable Quizzes**: Generate quizzes based on topics, difficulty levels, and question types (MCQs, True/False, Short Answer, etc.).
- **Adaptive Learning**: Tailors questions to user proficiency levels for an optimal learning experience.
- **Rich Question Formats**: Supports text-based, image-based, and code-based question generation.
- **Intuitive UI**: Easy-to-use interface for specifying quiz preferences and viewing results.
- **Export Options**: Download quizzes as PDFs or in JSON format for integration with other systems.

---

## Prerequisites

### Software Requirements
- Python 3.8+
- Virtual Environment (recommended)



## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Monisha09-ds/Interview_MCQ_generation.git
   cd AI_Quiz_Generation_System
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv mcq
  # On Windows: mcq\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r req.txt
   ```

4. **Set Up API Keys**
   - Obtain an API key from GroqAPI key for GPT-based quiz generation.
   - Add the API key to a `.env` file in the project root:
     ```
    GROQ_API_KEY = api_key
     ```

---

## Usage

### Running the System

1. **Start the Application**
   ```bash
   streamlit run app.py
   ```

2. **Customize Your Quiz**
   - Specify the topic, number of questions, difficulty level, and question format.

3. **Generate and Export**
   - Review the generated quiz.
   - Download the quiz in PDF or JSON format.

---

## Project Structure

```plaintext
AI_Quiz_Generation_System/
├── data/                # Optional directory for storing pre-existing pdf
├── results/             # saved quiz scores
├── app.py               # Streamlit application script
├── export_utils.py      # Utility functions for exporting quizzes
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── .env                 # Environment variables (not included in repo)
└── assets/              # Static files (e.g., images for questions)
```

---

## Customization

- **Adding Question Types**: Extend `quiz_generator.py` to include new question types or formats.
- **Localization**: Adapt the system for multiple languages by integrating translation APIs.
- **Enhanced UI**: Modify `app.py` to include additional customization options for users.

---

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- [Groq](https://console.groq.com/keys) for API key
- [Streamlit](https://streamlit.io/) for the user interface framework

---

Happy learning! 🎉
