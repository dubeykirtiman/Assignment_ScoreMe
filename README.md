
PDF to Data Sheet Converter



Installation & Setup

1. Download zip or clone it on your desktop.
2. Install the required dependencies:

-> Install the latest tesseract-ocr-w64-setup-xxx.exe in your system from the link : https://github.com/tesseract-ocr/tesseract/releases 
-> Install poppler in your system from the link : https://github.com/oschwartz10612/poppler-windows/releases (Copy path of bin to system variable)
-> pip install pandas openpyxl PyMuPDF
-> install jupyter notebook in your system through : pip install jupyter notebook (in CMD)



How to Run

1. Open either `testingpdf1.ipynb` or `testingpdf2.ipynb` using Jupyter Notebook:

In CMD : python - m notebook (to open jupyter notebook)

2. Follow the notebook cells step-by-step to:

   - Load the PDF.
   - Extract raw text or tabular data.
   - Format and save the results to Excel files.

3. View the outputs like `final_converted_data.xlsx` for the processed results.



Some important points :

- The notebook is currently configured to read the sample PDFs: `testingpdf1.pdf` and `testingpdf2.pdf`.
- To use your own PDFs, just replace the filenames in the notebook code.
- The structure assumes financial tables. Adjust parsing logic as needed for other layouts.




Requirements Summary

- Python 3.7+
- pandas
- openpyxl
- PyMuPDF (also installed as `fitz`)

