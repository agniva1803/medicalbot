This is the code of this paper: Task-oriented Dialogue System for Automatic Diagnosis.

A Medical-domain Dialogue System for Diseases Identification. Both the symptoms and the diseases are treated as slots as in the conventional dialogue systems. There is only one agent in the dialogue system, who is in charge of both symptom selection and disease prediction.

##Data
Our dataset is available here or can be found at the homepage of Prof. Wei. Please read the README.txt in the zip file and our paper for the details about our dataset.

How to use
Downloading our dataset.
Putting the dataset in a directory and pointing the path of the dataset in src/dialogue_system/run/run.py
Using the following command to see how to run this code, i.e., each parameter in the code.
cd src/dialogue_system/run
python run.py --help

##Cite
@inproceedings{wei2018task,
  title={Task-oriented Dialogue System for Automatic Diagnosis},
  author={Liu, Qianlong and Wei, Zhongyu and Peng, Baolin and Tou, Huaixiao and Chen, Ting and Huang, Xuanjing and Wong, Kam-Fai and Dai, Xiangying},
  booktitle={Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)},
  volume={2},
  pages={201--207},
  year={2018}
}
