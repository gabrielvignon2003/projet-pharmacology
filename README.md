# projet-pharmacology

This repository contains most of the code I have made during my research internship. The project was to study Pharmacology with the Science of Science approach.

# How to use this repository

- **sources_and_works_extraction** will allow you to extract the datasets I have used to study Pharmacology. This have been made using the API of the OpenAlex database. The notebook also contains a first basic analysis of the journals (the sources).

- **works_eda** contains most of the data analysis. You can execute it until the topic modelling section, where you will be able to download the transformed dataset that will be used for doing the topic modelling.

- At this point, you can use the **nlp** notebook to do the topic modelling. Executing this notebook on GPUs is highly recommended. **nlp** notebook also contains some basic analysis of the topic modelling results. 

- After that step, you can come back to the **works_eda**  noteback and finish the execution. At the end, you will be able to download a new dataset that will be used for the Machine Learning predictions.

- For doing this predictions, you can simply execute the **modelling dataset**

- In parallel, you can also execute the coauthorshipnetwork notebook. In the notebook, we use Graphistry and Networkx but Gephi can also be used outside of the notebook (once the edges dataset downloaded).

# Other resources

**video_topic_pharmacology** is a mp4 video that shows the evolution of Pharmacology, it can also be manually computed in the **works_eda** notebook.
the **BJP** folder contains similar notebooks that have been used for a smaller dataset containing only works of the British Journal of Pharmacology. A slide presentation summarizing this analysis is also available.
