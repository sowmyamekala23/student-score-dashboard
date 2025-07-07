# Student Scores Analysis

This project analyzes the scores of 100 students across 5 subjects using Python and NumPy, providing statistical insights and visualizations of the data.

## Features

- **Random Data Generation**: Generates random scores between 50 and 100 for 100 students in 5 subjects.
- **Statistical Analysis**:
  - Calculates subject-wise minimum, average, and maximum scores.
  - Identifies the best and worst performing students based on total scores.
  - Counts the number of students scoring above 90 in any subject.
  - Computes median, 10th, 25th, 50th, 75th, and 90th percentiles of total scores.
  - Identifies students in the top 10%, bottom 10%, and middle 50% performance bands.
- **Visualization**:
  - Bar chart showing average scores per subject.
  - Boxplot displaying the distribution of scores for each subject.

## Requirements

- Python 3.x
- NumPy
- Matplotlib

Install dependencies using:
```bash
pip install numpy matplotlib
```

## Usage

Run the script:
```bash
python <script_name>.py
```

Replace `<script_name>.py` with the filename containing the code.

## Output

- Console output with statistical analysis of student scores.
- **Bar Chart**: Visualizes the average scores for each subject.
- **Boxplot**: Shows the distribution of scores in each subject.

## Example Output

```
Subject-wise minimum score :  [53 51 50 51 50]
Subject-wise average score :  [77.47 76.62 75.01 74.48 75.47]
Subject-wise maximum score :  [100 100 100 100 100]
Best student: index 48 with 487 points
Worst student: index 4 with 272 points
Number of students scoring >90 in any subject: 98
Median (50th percentile) total score: 376.0
Top (10%) Threshold total score: 426.0
Number of student scored above 90th percentile: 10
maximum score among the bottom 10% of students: 316.0
Number of students in bottom 10% of students: 10
Number of students in the middle 50% range: 50
```

Two plots will be displayed:
- **Average Scores per Subject (Bar Chart)**
- **Distribution of Scores per Subject (Boxplot)**

## Customization

You can modify the number of students, subjects, or the score range by changing the following variables in the script:
```python
students = 100
subjects = 5
scores = np.random.randint(50, 101, size=(students, subjects))
```

## License

This project is licensed under the MIT License.