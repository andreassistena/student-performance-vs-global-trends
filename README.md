# student-performance-vs-global-trends

### Dataset 1: UCI Student Performance (student-mat.csv)

- **Why I chose this dataset**: This dataset provides real-world student performance data from Portuguese secondary schools. It includes various academic and behavioral variables such as study time, absences, final grades, and support programs.
  
- **How I gathered it**: I manually downloaded the dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance) as a `.zip` file. I extracted and used the `student-mat.csv` file for analysis.

- **Variables used**:
  - `G3`: Final grade
  - `studytime`: Weekly study time
  - `internet`: Whether the student has internet access at home
  - `absences`: Number of school absences

### Dataset 2: Predict Students' Dropout and Academic Success (student_dropout.csv)

- **Why I chose this dataset**: Provides a large, clean dataset of 4,424 undergraduate records that include demographic, socioeconomic, and academic features related to dropout risk and academic performance :contentReference[oaicite:8]{index=8}.
- **How I gathered it**: I manually downloaded the dataset from the UCI Machine Learning Repository in .zip format and extracted the `student_dropout.csv` file.
- **Key variables**:
  - `target`: Student outcome — 'dropout', 'enrolled', or 'graduate'
  - `previous_qualification`: Highest education level before enrollment
  - `age`, `marital_status`, `application_mode`
  - `units_approved_sem1`, `units_enrolled_sem2`, etc. (academic performance indicators)
