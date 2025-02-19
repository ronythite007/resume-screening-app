# Resume Screening Project

## Overview
This project focuses on automating resume screening using a combination of regular expressions for text extraction and a KNeighborsClassifier for classification. The goal is to efficiently filter and categorize resumes based on predefined criteria.

## Features
- Extracts relevant information (e.g., name, contact details, skills, experience) using regular expressions.
- Uses the K-Nearest Neighbors (KNN) algorithm for resume classification.
- Supports multiple resume formats (TXT, PDF, DOCX).
- Provides classified output eg(Data Science,Machine Learning,Lawyer)

## Technologies Used
- Python
- Regular Expressions (`re` module)
- Scikit-learn (`KNeighborsClassifier`)
- PDF and DOCX parsing libraries (`pdfplumber`, `python-docx`)
- Pandas for data processing

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/resume-screening.git
   cd resume-screening
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place resumes in the `resumes/` folder.
2. Run the script:
   ```bash
   python main.py
   ```
3. The script will extract information, classify resumes, and output results in `output.csv`.

## Folder Structure
```
resume-screening/
│-- resumes/        # Folder containing resume files
│-- main.py         # Main script for extraction and classification
│-- model.py        # Contains KNN model implementation
│-- requirements.txt # List of dependencies
│-- README.md       # Project documentation
```

## How It Works
1. **Text Extraction**:
   - Regular expressions identify key details (name, email, phone, skills, etc.).
2. **Feature Engineering**:
   - Extracted text is converted into structured features for model training.
3. **Classification using KNN**:
   - The model classifies resumes into relevant categories based on trained data.

## Future Improvements
- Improve text extraction accuracy with NLP techniques.
- Implement a web interface for easy interaction.
- Expand classification models using deep learning.

## License
This project is licensed under the MIT License.

## Contact
For any queries, feel free to reach out at `rohanthite9293@gmail.com`.

