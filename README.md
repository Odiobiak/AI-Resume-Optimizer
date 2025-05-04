# AI-Resume-Optimizer

# Resume Optimizer

This project uses the power of Google's Gemini AI model to analyze, optimize, and refine your resume based on a target job description. It also generates a tailored cover letter to enhance your application.

## Features

- **Resume Analysis:** Identifies strengths, gaps, and areas for improvement in your resume compared to the job description.
- **Resume Refinement:** Intelligently rewrites your resume, prioritizing keywords, highlighting relevant experience, and quantifying achievements.
- **Cover Letter Generation:** Creates a personalized cover letter that showcases your qualifications and addresses potential gaps.
- **Compatibility Check:** Assesses the compatibility between your resume and the job description, offering alternative roles if needed.
- **Semantic Match Score:** Provides a score indicating the semantic similarity between your resume and the job description using embeddings.

## How it Works

1. **Input:** Upload your resume and the target job description (PDF, DOCX, or TXT).
2. **Analysis:** The code extracts text from the documents and analyzes their alignment using Gemini.
3. **Refinement:** Based on the analysis, the code generates an optimized version of your resume.
4. **Cover Letter:** A tailored cover letter is crafted using the refined resume and job description.
5. **Output:** You can download the optimized resume and cover letter as text files.

## Requirements

- Python 3.7 or higher
- Google Generative AI library (`google-generativeai`)
- python-docx library (`python-docx`)
- PyPDF2 library (`PyPDF2`)
- scikit-learn library (`sklearn`)
- Google Colab environment (recommended)

## Installation

1. Install the required libraries: bash pip install google-generativeai python-docx PyPDF2 sklearn

2. Set up a Google Cloud project and enable the Generative Language API.
3. Obtain an API key and configure it in the code.

## Usage

1. Upload the code to your Google Colab notebook.
2. Run the `main()` function.
3. Follow the prompts to upload your resume and job description.
4. The optimized resume and cover letter will be downloaded automatically.

## Disclaimer

This tool is intended to assist you in improving your resume and cover letter. It's crucial to review the generated content and make any necessary adjustments before submitting your application.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
