# sustainability-rule-of-law
Due to GitHub size restrictions, [link to the jupyter notebook on Google Collab](https://colab.research.google.com/drive/1aVJE7KzIdl8Hts7QEvpV446j-mHoD2hk?usp=sharing)     
    
In this project I offer a visual story about the relationship between nations' commitment to environmental sustainability and their adherence to the rule of law.     
This project is inspired by the idea that the principles of the rule of law, advocating for equitable treatment and accountability, may reflect the core values of sustainable environmental practices.     

For the sustainability data, my reference was the latest results of the Environmental Performance Index (EPI) rankings, conducted by Yale. Rule of law data was obtained from the World Competitiveness Ranking (IMD) report.    

* **Pandas and GeoPandas, Altair, Seaborn, and Matplotlib** are the key libraries used.    
* The project featured an interactive map connected with a bar chart, designed to showcase global environmental performance overall score to enable a clear, visual representation of how different regions across the world compare in terms of sustainability efforts.     
![Interactive Map and Bar Chart](https://github.com/merts3ger/sustainability-rule-of-law/blob/main/epi.jpg "Interactive Map and Bar Chart Visualization")      
    
* It is followed by a scatter plot to look at the relationship between countries' EPI rankings and their RoL scores. Here it seemed already apparent there's a correlation between the two:    
![Scatter Plot of EPI Rankings vs RoL Scores](https://github.com/merts3ger/sustainability-rule-of-law/blob/main/comparisonEPIROL.jpg "Scatter Plot Visualization")
       
* Lastly, to support the gained visual insights, Spearman correlation analysis was conducted, resulting in a correlation matrix:    
![Spearman Correlation Matrix](https://github.com/merts3ger/sustainability-rule-of-law/blob/main/corrmatrix.jpg "Correlation Matrix")    
    
The substantial positive correlations observed between environmental performance rankings and adherence to the rule of law standards suggested a meaningful relationship. The visualizations also highlighted the contrast in the performance of different regions, as well as some outstanding examples.   
