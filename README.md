# Certificate Generator with Student Data

Welcome to the "Certificate Generator" repository. This Python script uses the Pillow and Openpyxl libraries to generate personalized digital certificates from student data stored in an Excel spreadsheet.

## How to Use

**Student Spreadsheet:** Make sure to have a spreadsheet named 'planilha_alunos.xlsx' with necessary information such as course name, participant's name, participation type, duration, start date, end date, and issuance date.

**Default Certificate:** Provide a certificate template in image format (certificado_padrao.jpg), where student data will be overlaid.

**Font Configuration:** Add the necessary fonts (tahomabd.ttf and tahoma.ttf) to the same directory as the script.

**Script Execution:** Run the 'gerador_certificados.py' script to process the spreadsheet data and generate individual certificates for each student.

## Requirements

Ensure all dependencies are installed:

```bash
pip install pillow openpyxl
