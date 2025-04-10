# Alzheimer's Disease Risk Assessment System

A comprehensive web application that uses machine learning and cognitive tests to assess Alzheimer's disease risk. The system combines multiple cognitive assessments to provide a comprehensive risk evaluation.

![Project Logo](static/images/logo.png) <!-- Add your logo if available -->

## Table of Contents

- [Features](#features)
- [Technical Stack](#technical-stack)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Security](#security)
- [Contributing](#contributing)
- [License](#license)

## Features

### User Authentication

- Secure login and signup system
- Session management
- Password hashing with bcrypt

### Cognitive Tests

- **Handwriting Analysis Test**: Evaluates motor skills and cognitive function
- **Memory Matrix Test**: Assesses memory and pattern recognition
- **Stroop Test**: Measures cognitive flexibility and processing speed

### Machine Learning Integration

- Multiple model support:
  - Random Forest Classifier
  - XGBoost Classifier
  - Gradient Boosting Classifier
- Real-time risk assessment
- Comprehensive model evaluation metrics

### Data Management

- Supabase integration for secure data storage
- Metrics tracking and analysis
- User result history and visualization

### Interactive Dashboard

- Real-time test results
- Risk score visualization
- Historical data analysis
- User-friendly interface

## Technical Stack

### Backend

- Python 3.x
- Flask web framework
- scikit-learn for machine learning
- XGBoost for advanced ML models
- pandas and numpy for data processing

### Frontend

- HTML5
- CSS3
- JavaScript
- Interactive visualizations

### Database

- Supabase for secure data storage
- Environment variable configuration

## Installation

1. Clone the repository:

```bash
git clone [your-repository-url]
cd final-part1
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Configuration

1. Create a `.env` file in the root directory with the following variables:

```
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
```

2. Ensure all model files are present in the `models/` directory:

- `random_forest_model.pkl`
- `xgboost_model.pkl`
- `gradient_boosting_model.pkl`
- `scaler.pkl`

## Usage

1. Start the application:

```bash
python app.py
```

2. Access the application at `http://localhost:5000`

3. Create an account or login to begin assessments

## Project Structure

```
final-part1/
├── app.py                  # Main application file
├── models/                 # Machine learning models
├── static/                 # Static assets (CSS, JS, images)
├── templates/              # HTML templates
├── data/                   # Data storage
├── .env                    # Environment variables
├── requirements.txt        # Python dependencies
└── README.md              # Documentation
```

## Security

- Secure session management with configurable lifetime
- Password hashing using bcrypt
- Environment variable configuration
- Secure cookie settings
- CSRF protection
- Input validation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [scikit-learn](https://scikit-learn.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Supabase](https://supabase.io/)
- [XGBoost](https://xgboost.readthedocs.io/)

## Contact

[Your Name] - [Your Email]

Project Link: [https://github.com/yourusername/final-part1](https://github.com/yourusername/final-part1)
