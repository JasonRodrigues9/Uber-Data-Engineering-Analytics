# Uber-Data-Engineering-Analytics
In this project i have analyzed Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio. 

💻 STEPS UNDERTAKEN
1. Extracted the data from the Uber dataset and loaded it onto the Google Cloud Storage.
2. Transformed and modelled the data using fact and dimensional data modelling schema in Jupyter Notebook using Python.
3. Implemented the ETL process with the data pipeline on Mage and loaded the transformed data onto Google BigQuery for further analysis.
4. Developed the dashboard on Looker.

🚧 Blockages observed & 🕵‍♂️ tactics implemented
1. The cloud instance of GCP is quite scalable for many projects. However, the processing time taken with lower computing power is too long. 4 CPUs and 16GB of memory works well.
2. Mage would shut down after an inactivity period of 15 minutes. To tackle this problem, the SSH had to be run again with the correct prompts.
3. Firewall authentications rules should be established well for running the entire ETL process successfully.

📊 Insights from the dashboard
1. Average long distance trips were mostly undertaken by 1-2 passengers who prefer to pay by Cash.
2. Most revenue generated were paid by Credit Cards.
3. Westchester and Newark rate codes contribute to the most revenue being generated.
4. Most pick-ups and drop-offs where accounted on the 10th and 11th of every month respectively.

