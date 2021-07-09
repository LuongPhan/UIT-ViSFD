# UIT-ViSFD
Author: Luong Luc Phan et al., 2021 \
Institute: University of Information Technology-VNUHCM, Vietnam\
Email: 18521073@gm.uit.edu.vn\
Link paper: https://arxiv.org/pdf/2105.15079.pdf \
Please cite to the following journal when using the dataset:

      @article{phan2021sa2sl,
      title={SA2SL: From Aspect-Based Sentiment Analysis to Social Listening System for Business Intelligence},
      author={Phan, Luong Luc and Pham, Phuc Huynh and Nguyen, Kim Thi-Thanh and Nguyen, Tham Thi and Huynh, Sieu Khai and Nguyen, Luan Thanh and Van Huynh, Tin and Van Nguyen, Kiet},
      journal={arXiv preprint arXiv:2105.15079},
      year={2021}
}


# Data Information:
We crawl textual feedback from customers about smartphones on a large e-commerce website in Vietnam. The label of the dataset is ten aspects and three polarities. Please read the guidelines in the [paper](https://arxiv.org/pdf/2105.15079.pdf) for more information. We randomly divide the dataset into three sets: 
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
  
  
