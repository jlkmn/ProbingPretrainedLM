![build](https://github.com/JlKmn/ProbingPretrainedLM/actions/workflows/ci.yml/badge.svg)
# Probing Pre-trained Language Models

## Getting started
1. Clone the repo\
`git clone https://github.com/JlKmn/ProbingPretrainedLM.git`
1. Create virtualenv\
`python -m venv env`
2. Activate virtualenv\
`source env/bin/activate`
3. Install requirements\
`pip install -r requirements.txt`
4. Log into wandb\
`wandb login`
5. Start training\
`python run.py --model 1 --dataset pos --epochs 5`
