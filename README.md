
# Description
Generate personalized cover letters by analyzing job postings and the user's CV.

## Initial Setup
First, create a dedicated virtual environment to manage dependencies:
```bash
python3 -m venv env
```

Next, activate the virtual environment:
```bash
source env/bin/activate
```

Finally, install all the required dependencies:
```bash
pip install -r requirements.txt
```

Finally, replace the job url and the ./cv.pdf file

### Required Parameters
- `--link_to_job`: The URL of the job posting you're applying to.
- `--cv_pdf_path`: The file path to your CV, which must be in PDF format.
- `--openai_key`: Your OpenAI API key for accessing GPT models.

### Usage Example
Run QuickCoverLetter with the following command:
```bash
bash create_cover_letter \
  --job_url="https://www.linkedin.com/jobs/view/3778594855" \
  --cv_file_path="./cv.pdf" \
  --openai_api_key="<api_key>"
```

### Output

Dear Sir or Madam,

I am writing to express my keen interest in the Data Engineer apprenticeship opportunity at LVMH Recherche, starting September 2025. Currently enrolled in the Master 2 MIAGE program at the University of Orléans, I am eager to contribute to a prestigious and innovative organization like LVMH, where data and technology enhance excellence in luxury and beauty.

Through my experience as a Data Engineer at Optibot, I have developed and maintained ETL pipelines using Python to structure and integrate data for local SMEs. I worked with modern stacks including React and SUPABASE, which aligns with your emphasis on designing scalable data architectures and maintaining high-quality data integration. My role required autonomy, rigorous organization, and strong communication to deliver reliable solutions in a dynamic context.

Additionally, my internship at PyratzLabs sharpened my ability to handle complex systems. I developed an arbitrage bot on the Ethereum Virtual Machine using Python, JavaScript, and Solidity, involving API consumption, data transformation, and performance monitoring—skills highly transferable to your GCP-based infrastructure and Streamlit application development.

My academic projects have further refined my data processing and analytical skills. For example, a socioeconomic health study allowed me to apply clustering and regression techniques using R and Python, reinforcing my ability to derive insights from raw data. I am familiar with Git, Linux environments, and Agile practices, and I have a genuine passion for innovation and the luxury sector—values that deeply resonate with LVMH’s mission.

I am enthusiastic about the opportunity to bring my technical expertise, entrepreneurial spirit, and collaborative mindset to your Data & Digital team. Thank you for considering my application. I would welcome the chance to discuss how I can contribute to your vision.

Sincerely,
Rayane Saadallah


