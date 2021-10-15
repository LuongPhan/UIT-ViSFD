# UIT-ViSFD
Author: Luong Luc Phan et al., 2021 \
Institute: University of Information Technology-VNUHCM, Vietnam\
Email: 18521073@gm.uit.edu.vn\
Link paper: [link](https://link.springer.com/chapter/10.1007/978-3-030-82147-0_53?fbclid=IwAR00G3h4feqS5m_hu8lMbwLw22bXqOjBLrpBzs25eszMN9d7UPjjaCTEcpw) \
Please cite to the following conference when using the dataset:

      @InProceedings{10.1007/978-3-030-82147-0_53,
      author="Luc Phan, Luong
      and Huynh Pham, Phuc
      and Thi-Thanh Nguyen, Kim
      and Khai Huynh, Sieu
      and Thi Nguyen, Tham
      and Thanh Nguyen, Luan
      and Van Huynh, Tin
      and Van Nguyen, Kiet",
      editor="Qiu, Han
      and Zhang, Cheng
      and Fei, Zongming
      and Qiu, Meikang
      and Kung, Sun-Yuan",
      title="SA2SL: From Aspect-Based Sentiment Analysis to Social Listening System for Business Intelligence",
      booktitle="Knowledge Science, Engineering and Management ",
      year="2021",
      publisher="Springer International Publishing",
      address="Cham",
      pages="647--658",
      abstract="In this paper, we present a process of building a social listening system based on aspect-based sentiment analysis in Vietnamese, from creating a dataset to building a real application. Firstly, we create UIT-ViSFD, a Vietnamese Smartphone Feedback Dataset, as a new benchmark dataset built based on a strict annotation scheme for evaluating aspect-based sentiment analysis, consisting of 11,122 human-annotated comments for mobile e-commerce, which is freely available for research purposes. We also present a proposed approach based on the Bi-LSTM architecture with the fastText word embeddings for the Vietnamese aspect-based sentiment task. Our experiments show that our approach achieves the best performances (in F1-score) of 84.48{\%} for the aspect task and 63.06{\%} for the sentiment task, which performs several conventional machine learning and deep learning systems. Lastly, we build SA2SL, a social listening system based on the best performance model on our dataset, which will inspire more social listening systems in the future.",
      isbn="978-3-030-82147-0"
      }

If any company utilizes the dataset for commercial purposes, please contact us via email: 18521073@gm.uit.edu.vn.
# Data Information:
We crawl textual feedback from customers about smartphones on a large e-commerce website in Vietnam. The label of the dataset is ten aspects and three polarities. Please read the guidelines in the [paper](https://link.springer.com/chapter/10.1007/978-3-030-82147-0_53?fbclid=IwAR00G3h4feqS5m_hu8lMbwLw22bXqOjBLrpBzs25eszMN9d7UPjjaCTEcpw) for more information. We randomly divide the dataset into three sets: 
- Train: 7,786.
- Dev: 1,112.
- Test: 2,224.
# Attribute Information:
The dataset consists of 11,122 comments, including of four features:
- comment: Commentary content.
- n_star: The user evaluates the smartphone's star.
- data_time: The date and time the comment was posted.
- label: Label of comment.\
All samples are in text format. No tokenization has been applied. Users of this dataset are free to use whatever sentence representation they choose.  
  
  
