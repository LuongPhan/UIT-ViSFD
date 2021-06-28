# UIT-ViSFD
Author: Luong Luc Phan et al., 2021 \
Institute: University of Information Technology-VNUHCM, Vietnam\
Email: 18521073@gm.uit.edu.vn\
Link paper: https://arxiv.org/pdf/2105.15079.pdf \
Please cite to the following journal when using the dataset:

      @misc{phan2021sa2sl,
      title={SA2SL: From Aspect-Based Sentiment Analysis to Social Listening System for Business Intelligence}, 
      author={Luong Luc Phan and Phuc Huynh Pham and Kim Thi-Thanh Nguyen and Tham Thi Nguyen and Sieu Khai Huynh and Luan Thanh Nguyen and Tin Van Huynh and Kiet Van Nguyen},
      year={2021},
      eprint={2105.15079},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}


# Data Information:
We crawl textual feedback from customers about smartphones on a large e-commerce website in Vietnam. The label of the dataset is ten aspects and three polarities. Please read the guidelines in the paper for more information. We randomly divide the dataset into three sets: \
	Train: 7,786.\
	Dev: 1,112.\
	Test: 2,224.
# Attribute Information:
The dataset consists of 11,122 comments, including of four features:\
	  comment: Commentary content.\
	  n_star: The user evaluates the smartphone's star.\
	  data_time: The date and time the comment was posted.\
	  label: Label of comment.\
All samples are in text format. No tokenization has been applied. Users of this dataset are free to use whatever sentence representation they choose.  
  
  
