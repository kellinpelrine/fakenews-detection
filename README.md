# fakenews-detection

To install, run the following:

conda env create -f environment.yml

conda activate fakenews-detection

python install.py


Example usage (the higher the score, the more similar the domain is to known fake news domains)

- get fakeness score for a mainstream domain 
`python sample_predict_domain_score.py  --domain wsj.com`

- get fakeness score for a low quality domain 
`python sample_predict_domain_score.py  --domain trumptrainnews.com`


Contact: Zhouhan Chen, zhouhan.chen@nyu.edu

	
