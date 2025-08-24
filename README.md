This repository contains most of the code I developed during my research internship. The project aimed to study Pharmacology using a Science of Science approach.

# How to use this repository

- **sources_and_works_extraction** allows you to extract the datasets used for studying Pharmacology. This was done using the OpenAlex API. The notebook also includes a basic first analysis of journals (the sources).

- **works_eda** contains most of the data analysis. You can run it until the topic modeling section, at which point you will be able to download the transformed dataset required for topic modeling.

- Next, you can use the **nlp** notebook to perform topic modeling. Running this notebook on GPUs is highly recommended. It also includes some basic analyses of the topic modeling results.

- After completing this step, you can return to the **works_eda** notebook and finish running it. At the end, you will be able to download a new dataset that will be used for Machine Learning predictions.

- To run these predictions, simply execute the **modelling** notebook.

- In parallel, you can also run the **coauthorshipnetwork notebook**. It uses Graphistry and NetworkX, but Gephi can also be used externally once the edges dataset has been downloaded.

# Other resources

- **bcr_5ysmoothing** is an MP4 video showing the evolution of Pharmacology. It can also be generated manually in the **works_eda** notebook.

- The **BJP folder** contains similar notebooks for a smaller dataset consisting only of works from the British Journal of Pharmacology. A slide presentation summarizing this analysis is also available.
