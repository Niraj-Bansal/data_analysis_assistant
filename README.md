
# Data Analysis Assistant

A conversational AI Assistant to perform data analysis on multiple CSVs at once in a chat-based interface.

Upload multiple csv files, confirm the correctness of the data parsing and voila ! begin commanding the AI assistant
to perform data analysis tasks on the files.

### Assuming Titanic data is uploaded, ask questions like : -
(1)  What is the median age of survivors vs non survivors ?

(2) What is the passenger distribution between sexes ?

(3) Who is the oldest Passenger ?

etc...


[Expect outputs in markdown format, the update version with tablular and graphical outputs is awaited...]




## Run Locally

Clone the project

```bash
  git clone https://github.com/Niraj-Bansal/data_analysis_assistant.git
```

Go to the project directory

```bash
  cd data_analysis_assistant
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Deploy as a streamlit web app locally

```bash
  streamlit run main.pyo
```

