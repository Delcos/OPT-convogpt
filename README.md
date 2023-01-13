# OPT-convogpt
This is an updated version of convogpt that I've modified to run OPT models. It can also run any other LLM pytorch model with just 2 lines of code being changed to whatever model you're using.

Aside from this, it is now able to get repeated inputs instead of running once and outputting a value.

## ⚙️ Pretrained Models
| Model ID   | Parameter Count | Training Method |
|------------|-----------------|-----------------|
| [convogpt-125m-uft](https://huggingface.co/hakurei/convogpt/tree/main/125m-uft) | 125 Million | Unsupervised Finetuning |
| [convogpt-1.3b-uft](https://huggingface.co/hakurei/convogpt/tree/main/1.3b-uft) | 1.3 Billion | Unsupervised Finetuning |
| [convogpt-2.7b-uft](https://huggingface.co/hakurei/convogpt/tree/main/2.7b-uft) | 2.7 Billion | Unsupervised Finetuning |
| [convogpt-6b-uft](https://huggingface.co/hakurei/convogpt/tree/main/6b-uft)     | 6 Billion   | Unsupervised Finetuning |

## 🔑 Setup

```shell
git clone git@github.com:harubaru/convogpt.git
cd convogpt
pip install protobuf==3.20.*
python -m pip install -r requirements
```

## 🤖 Inference
```python
```
