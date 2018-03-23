# ICA-4-Visuals
## Description of data.sets.sat_score

'''sql
SELECT school, avg(sat_writing) as avg_writing_score
from datasets.sat_scores 
group by school  
order by avg_writing_score desc 
'''
