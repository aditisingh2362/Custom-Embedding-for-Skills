# Custom-Embedding-for-Skills

#### Task
Given a dataset of candidate skills, we want to learn an embedding representation of each skill. The idea being similar to word embeddings where words of similar meaning like apple & orange lie closer to each other in the embedding space than semantically different words like apple & king. Similarly, in this case- once the embeddings is trained skills like Java & C++ should lie closer to each than say Java & Business Development. 

#### Dataset
Data is in the following format 
[[skill1, skill2, skill3, ...], [skill1, skill4, skill6, ...], ….]
Which a list of list of skills. Each internal list represents the skills of one given candidate and there are about 3M such skill vectors.


#### Steps Taken
1. Data clean up & preprocessing 
2. Represent the data in the format expected by your embedding model 
3. Train the embedding
4. Visualize it using tensorboard. 


