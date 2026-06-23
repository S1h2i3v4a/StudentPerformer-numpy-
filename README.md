# Student Performance Analyzer

A NumPy-based project to analyze student marks: averages, grades, top performers, and subject-wise insights.

## Features
- Per-student and per-subject average marks
- Grade calculation (loop + vectorized `np.select`)
- Highest/lowest marks (overall and per subject)
- Top performers ranking
- Subject-wise analysis (toughest/easiest subject)

## Technologies
- Python
- NumPy

## Sample Output
Top Performers in Each Subject:
Subject 1: Neha with mark 95.0
Subject 2: Neha with mark 92.0
Subject 3: Divya with mark 93.0
Subject 4: Neha with mark 97.0
Subject 5: Neha with mark 94.0

Lowest Performers in Each Subject:
Subject 1: Suresh with mark 40.0
Subject 2: Suresh with mark 45.0
Subject 3: Suresh with mark 38.0
Subject 4: Suresh with mark 50.0
Subject 5: Suresh with mark 42.0
Subjects toughest: Subject 1
Subjects easiest: Subject 4

## How to Run
```bash
python main.py
```

## Future Improvements
- Add Matplotlib charts
- Add CSV export of results