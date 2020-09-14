### **Find Objects and Focus on Highlights:  Mining Object Semantics for Video Highlight Detection via Graph Neural Networks**

#### Requirements

Python 3.6

torchvision==0.3.0

torch==1.1.0

scikit-image==0.15.0

opencv-python==4.1.0.25

imageio==2.5.0

dgl==0.3



#### Configuration

Fill **dataset, feat_dir, gpu** in the config_server.py

#### Training

python train.py

#### Testing

python eval.py

## Cite
@inproceedings{DBLP:conf/aaai/ZhangGYLLX20,
  author    = {Yingying Zhang and
               Junyu Gao and
               Xiaoshan Yang and
               Chang Liu and
               Yan Li and
               Changsheng Xu},
  title     = {Find Objects and Focus on Highlights: Mining Object Semantics for
               Video Highlight Detection via Graph Neural Networks},
  booktitle = {The Thirty-Fourth {AAAI} Conference on Artificial Intelligence, {AAAI}
               2020, The Thirty-Second Innovative Applications of Artificial Intelligence
               Conference, {IAAI} 2020, The Tenth {AAAI} Symposium on Educational
               Advances in Artificial Intelligence, {EAAI} 2020, New York, NY, USA,
               February 7-12, 2020},
  pages     = {12902--12909},
  year      = {2020},
  url       = {https://aaai.org/ojs/index.php/AAAI/article/view/6988},
}
