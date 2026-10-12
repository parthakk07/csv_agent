Ask questions in English about any CSV. Groq only picks which tool to call. Numbers come from pandas / sklearn, not from the model guessing

Demo table in the notebook is Social_Network_Ads.csv (400 rows). Swap the path to use a different file.
tools

- describe_data — shape, dtypes, missing, head, numeric summary
- missing_report — missing count and % per column
- value_counts — frequency of one column
- unique_values — nunique + sample values
- duplicated_data — extra duplicate rows
- filter_group_agg — pandas query, then groupby + sum/mean/count/min/max
- correlation — Pearson on numeric columns
- detect_outliers — IQR or z-score
- quick_model — tiny LogisticRegression or LinearRegression baseline
