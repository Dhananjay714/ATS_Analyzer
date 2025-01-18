# ATS Resume Analyzer

## Overview
The ATS Resume Analyzer is an AI-driven application aimed at helping job seekers enhance their resumes. It evaluates resumes in comparison to specific job descriptions, providing insights into their alignment. The tool delivers a match percentage, highlights missing keywords, and suggests improvements. Leveraging natural language processing and generative AI, it offers comprehensive feedback.

## Features
- **Resume Upload**: Upload resumes in PDF format.
- **Job Description Input**: Enter the job description for analysis.
- **Analysis Options**:
  - **Detailed Resume Review**: Offers an in-depth evaluation of the resume's relevance to the job description.
  - **Match Percentage Analysis**: Provides a percentage score reflecting the resume's match, highlights missing keywords, and identifies skill gaps.
- **Export Results**: Save the analysis results as a text file.
- **AI-Powered Insights**: Backed by Google Gemini AI to deliver expert evaluations and suggestions.

## Technologies Used
- **Streamlit**: For creating the user-friendly interface.
- **Google Gemini AI**: To perform the detailed analysis and calculate the match percentage.
- **PyPDF2**: For extracting text content from PDF files.
- **dotenv**: To securely manage API keys and configuration settings.

## Requirements
- **Python**: Version 3.7 or newer.
- **Google API Key**: Required for accessing Gemini AI.
- **Python Libraries**:
  - `streamlit`
  - `google-generativeai`
  - `PyPDF2`
  - `python-dotenv`

## Installation
1. Clone or download the repository:
   ```bash
   git clone https://github.com/yourusername/ATS_Resume_Analyzer.git
   cd ATS_Resume_Analyzer
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root folder and add your Google API key:
   ```env
   GOOGLE_API_KEY=your-google-api-key-here
   ```

4. Start the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## How to Use
1. **Upload Resume**: Use the "Upload your resume (PDF format)" option to add your resume.
2. **Enter Job Description**: Paste the job description into the provided text area.
3. **Select Analysis Type**: Choose either "Detailed Resume Review" or "Match Percentage Analysis".
4. **Run Analysis**: Click the "Analyze Resume" button to generate the results.
5. **Download Results**: Save the analysis output using the "Export Analysis" button.

## Example Analyses
- **Detailed Resume Review**: Delivers an extensive review highlighting strengths, gaps, and a final recommendation on your suitability for the role.

- **Match Percentage Analysis**: Displays the match percentage, identifies missing keywords, and offers skill gap improvement suggestions.

## Contribution
We welcome contributions! Feel free to open pull requests, report bugs, or propose new features.



