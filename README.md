# axiomatic_query_expansion
This is for TREC query expansion.
Please refer to 

Hui Fang and ChengXiang Zhai. 2006. Semantic term matching in axiomatic approaches to information retrieval. In Proceedings of the 29th annual international ACM SIGIR conference on Research and development in information retrieval (SIGIR '06). ACM, New York, NY, USA, 115-122. 

**Usage:**

use ```make``` to compile the binary.

You need the ```indri``` library to compile the binary.

Please refer to the sample files folder for the sample inputs of the binary.


**NOTE:**

The query ids can only be digits (e.g. 123), otherwise the results would be strange (all queries have the same <text> field)
