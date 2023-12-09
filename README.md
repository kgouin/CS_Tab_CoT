# CS-Tab-CoT

This is an implementation of CS-Tab-CoT: Zero-Shot Tabular Chain of Thought for Common Sense Reasoning Tasks.

This is an extension of Tab-CoT originally proposed by Ziqi Jin & Wei Lu. Their paper is available at [arXiv:2305.17812](https://arxiv.org/abs/2305.17812).

### Installing the requirements:
```
pip install -r requirements.txt
```

### Getting started:
To use this code, you must have an OpenAI API key, and set it as the environment variable "OPENAI_API_KEY".
```
export OPENAI_API_KEY=(YOUR OPENAI API KEY)
```

### Running the code:
To run the standard zero-shot method with the CommonSenseQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot
```
To run the Zero-shot-CoT method with the CommonSenseQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=15
```
To run the Tab-CoT method with the CommonSenseQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=1
```
To run the CS-Tab-CoT method with the CommonSenseQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=2
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=3
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=4
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=5
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=6
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=7
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=8
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=9
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=10
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=11
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=12
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=13
```
```
python main.py --model=gpt3-xl --dataset=commonsensqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=14
```
To run the standard zero-shot method with the StrategyQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot
```
To run the Zero-shot-CoT method with the StrategyQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=15
```
To run the Tab-CoT method with the StrategyQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=1
```
To run the CS-Tab-CoT method with the StrategyQA dataset using text-davinci-002:
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=2
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=3
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=4
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=5
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=6
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=7
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=8
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=9
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=10
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=11
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=12
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=13
```
```
python main.py --model=gpt3-xl --dataset=strategyqa --limit_dataset_size 0 --method=zero_shot_cot --cot_trigger_no=14
```