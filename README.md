Module 11 homework. This module was completed with the help of ChatGPT on the following lines of code: 
start_dates = mars_df[mars_df['ls'] == 0]['terrestrial_date']
start_dates = start_dates.sort_values()
martian_year_lengths = start_dates.diff().dt.days.dropna()
