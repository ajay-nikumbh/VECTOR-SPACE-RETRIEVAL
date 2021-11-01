
## Vector Space Retrieval
Objective : Install and experiment with Elasticsearch
and Kibana.

Vector space model or term vector model is an algebraic model for representing text documents (and any objects, in general) as vectors of identifiers (such as index terms).

It is used in information
filtering, information retrieval, indexing and relevancy rankings. It’s first use was in the SMART Information Retrieval
System. 


##  Elasticsearch | Kibana

Vector space retrieval can be done easily on elasticsearch
and kibana. we will look into few examples with their
pictorial representation as given below.



1.  Load the cran dataset .

![1  Load the cran dataset](https://user-images.githubusercontent.com/37560890/139626362-2161fd9a-7d45-461b-a999-5572e0302ece.png)


2.  Search for our index - cran_exp.

![2  Search the document](https://user-images.githubusercontent.com/37560890/139626473-b7c15c6c-57de-4942-8ae3-71b5176655f0.png)


3.  Getting a particular document by document id.

![3  Get a particular dataset](https://user-images.githubusercontent.com/37560890/139626576-d107443c-49b7-454b-b7dc-b6807dda5a0b.png)


4.  By using the jupyter notebook making a connection with elastic search and Kibana.

![4  Connection with](https://user-images.githubusercontent.com/37560890/139626733-7b2d3b60-a2b2-4dc8-b4d3-8fafc5b95843.png)


5.  Now we are going to perform query on our index and we will check the relevant document id's and match with our cran_rel doc ids and check relevance.

![5](https://user-images.githubusercontent.com/37560890/139627266-29915c7b-7a33-49dc-9350-c99264658df6.png)


6.  Below are the document id's which are retrieved by our system on index. Here we will give weight's to our title field i.e. 7 and we will get 40% relevant documents.

![6](https://user-images.githubusercontent.com/37560890/139627455-075fd3a0-c9c1-473a-ae6e-e45ef32d71a7.png)


7.  Now we are going to perform operation on query-2 and query as follows.

![7](https://user-images.githubusercontent.com/37560890/139628386-dee0c6c5-bac7-4a0a-8f0b-c03f204dacf6.png)

8.  Below are the retrieved document id's.

![8](https://user-images.githubusercontent.com/37560890/139628452-850f7e95-40ae-4422-af34-1fdda6486d84.png)

9.  We will match with cran_rel file.

![9](https://user-images.githubusercontent.com/37560890/139628516-173edd78-482a-4263-a8b2-9e9127c6c36a.png)



