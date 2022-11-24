On this repo you will find:
1 pptx file as a presentation dedicated to the storytelling for non techincal audience.
1 ('Data_analysis') R markdown (RMD format) that contains the code of the data analysis which explains the step followed along with the code and comments.
2 ('Modeling_same_day_orders' and 'Modeling_asap_orders') R markdown (RMD format) that regard machine learning models and the corresponding code and graphs along with comments. (Two different business scenarios to train the models) 
3 html document that have the same names as the above notebooks which include code, graphs, comments and generally the analysis as a draft report 
generated from the 3 R markdowns that I mentioned above, respectivelly. You can open the html with the browser of your choice.

My suggestion is to check the html documents directly to see the steps I followed in detail without 
having to run the code, which is also included on the document for illustration purposes. (Most of the graphs are interactive and you can hover over them to see the values)
You can first check the 'Data_analysis' html and then proceed with the 'Modeling_same_day_orders' which includes the preprocessing and the model development
based on the business assumptions made (more details in the presentation). 
The 'Modeling_asap_orders' has the same model development, code and logic but having outliers removed if the business decides accordingly.
The non-technical story telling is on the presentation document.

In case you want to run the markdowns locally you need RStudio.
The data and the markdown file has to be in the same folder and set this folder as directory using setwd("c:/example_directory").
To use the libraries used for this project you need to install them first in case you dont have them already 
by using install.packages('') command and include the library needed into the quotes.


