# CAP6135 - Term Project
### Phishing Detection Report Replication and Analysis

### Installation and Use
Run the following command in a fresh virtual environment

`pip3 install -r requirements.txt`  

To run the script:

`python3 code.py`

then, follow the prompts in the code.


### Paper
Link:  https://jis-eurasipjournals.springeropen.com/articles/10.1186/s13635-016-0034-3

### Description
This paper describes a novel implementation for phishing detection on the internet. For this project,
we will implement the phishing detection model and then we will compare our results with the
results of the original authors from their experiment.

### Dataset

After some research online, we found a github repo that contained a list of active phishing sites updated hourly.
This list of phishing sites will be used to determine the effectiveness of the detection algorithm we are attempting to replicate.

Link to repo: https://github.com/mitchellkrogza/Phishing.Database

### Citation to Paper
TY  - JOUR
AU  - Jain, Ankit Kumar
AU  - Gupta, B. B.
PY  - 2016
DA  - 2016/05/06
TI  - A novel approach to protect against phishing attacks at client side using auto-updated white-list
JO  - EURASIP Journal on Information Security
SP  - 9
VL  - 2016
IS  - 1
AB  - Most of the anti-phishing solutions are having two major limitations; the first is the need of a fast access time for a real-time environment and the second is the need of high detection rate. Black-list-based solutions have the fast access time but they suffer from the low detection rate while other solutions like visual similarity and machine learning suffer from the fast access time. In this paper, we propose a novel approach to protect against phishing attacks using auto-updated white-list of legitimate sites accessed by the individual user. Our proposed approach has both fast access time and high detection rate. When users try to open a website which is not available in the white-list, the browser warns users not to disclose their sensitive information. Furthermore, our approach checks the legitimacy of a webpage using hyperlink features. For this, hyperlinks from the source code of a webpage are extracted and apply to the proposed phishing detection algorithm. Our experimental results show that the proposed approach is very effective for protecting against phishing attacks as it has 86.02 % true positive rate while less than 1.48 % false negative rate. Moreover, our proposed system is efficient to detect various other types of phishing attacks (i.e., Domain Name System (DNS) poisoning, embedded objects, zero-hour attack).
SN  - 1687-417X
UR  - https://doi.org/10.1186/s13635-016-0034-3
DO  - 10.1186/s13635-016-0034-3
ID  - Jain2016
ER  - 

## Goals
For this project, we will be replicating the phishing detection model developed by the author's of the paper. To do this, we will implement the model in Python3. The model as well as the phishing detection algorithm can be seen below.

### Phishing Detection Model
This is taken directly from the author's of the paper linked above:

![image](https://user-images.githubusercontent.com/49283761/159128959-37272ac5-12ef-46ff-81cf-42c0b907be41.png)

### Algorithm
This is the phishing detection algoirthm for a webpage developed by the authors:

![image](https://user-images.githubusercontent.com/49283761/159129007-ff04293c-5b9b-456c-ade1-95b9ea6b35cb.png)

