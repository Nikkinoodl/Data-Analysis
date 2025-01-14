# Data-Analysis
The Excel workbook contains a sample of a chatbot data analysis.
Raw data was downloaded from a production database and uploaded to an Access database. Views were created to summarize the 50MB dataset.
The summarized data was uploaded to tables in Microsoft Excel using Microsoft PowerQuery, from where the final summarization and analysis was done.
The analysis was used to help in decision making and to give an overall view of progress rather than as a polished management presentation.
In this example, we created a bin for those with more than 5 conversations to roll-up the outliers and make the data easier to graph.
![Graph-3](https://github.com/user-attachments/assets/1c5e524a-e068-42e9-8ee6-c1cc89f488c4)
Simple linear regression was performed to help understand trends--this shows the results for just one of sixteen chatbots:
![Graph-4](https://github.com/user-attachments/assets/35a356d9-5a08-4233-b8f9-c5a094010de7)
Wherever possible, each chart was created to answer a business question. Inconsistencies in the distribution of ratings, for example, led to further analysis to understand whether this was a result of ratings manipulation:
![Graph-5](https://github.com/user-attachments/assets/b24dc839-f973-4689-b53d-43c1e3cf5b33)
The analysis attempted to understand the data from a nuanced business viewpoint. In doing so, it highlighted the need to be able to work with the data at a low level (e.g. SQL, or code), rather than via a code-free BI tool:
![Table-1](https://github.com/user-attachments/assets/ecabb01e-94d0-4a68-887d-da1e0880e5fc)
![Graph-1](https://github.com/user-attachments/assets/b2442b99-1b66-4571-8c5c-4344d14ca019)
We split some analysis between employee and non-employee users to see if the response from these more technology savvy users was different from that of the general public.
