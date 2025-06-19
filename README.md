
# Stroke Rehabilitation Score Pattern Analysis using ROM Labels

This project explores score patterns and streaks in rehabilitation game data for **stroke patients**, using ROM (Range of Motion) classification as the primary label. By identifying score distributions, repeated performance streaks, and outlier behaviors, the analysis aims to highlight subtle trends in patient motor recovery through game-based therapy data. A small mock dataset is included for demonstration and reproducibility.

## Features

- Score distribution histograms grouped by ROM class
- Streak analysis: identifying repeated score patterns per patient
- Outlier clipping for cleaner visual insight
- Reproducible Jupyter Notebook
- Mock dataset included for testing and demonstration

## File Structure

```
rom_score_analysis_project/
├── ROM_Score_Analysis.ipynb       # Main Jupyter Notebook with code and analysis
├── data/
│   └── user_data_with_label.txt   # Cleaned dataset (mock)
└── README.md                      # Project overview
```

## Notes

This project is built on a **mock dataset** simulating stroke rehabilitation scores from game-based motion tracking. While not based on real clinical data, the logic is designed to demonstrate methods of ROM-based trend and pattern recognition.

## Future Directions

- Apply to real-world rehabilitation datasets
- Integrate with time-series or temporal sequence modeling
- Collaborate with clinicians to refine ROM categorization criteria

