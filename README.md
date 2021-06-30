# Thai GPT Next

It is fine-tune the GPT-Neo model for Thai language.

**Dataset for fine-tune this model**

- prachathai67k
- thaisum
- thai_toxicity_tweet
- wongnai reviews
- wisesight_sentiment
- TLC
- scb_mt_enth_2020 (Thai only)
- Thai wikipedia (date: 2021/06/20)

**Max Length:** 280

**Number of train lists**: 1,697,254 lists

**Number of training**: 2 ep

**training loss**: 0.285500

## Model

- thaigpt-next-125m is fine-tune the GPT-NEO-125M model.

## FIle

- train.ipynb is train notebook of thaigpt-next-125m model.
- text_generation.ipynb is a text generation notebook.
- Few_shot_learning.ipynb is a few-shot learning notebook.

## How to use

You can using it from huggingface or PyThaiNLP (in the future) for few-shot learning works or text generation (not recommended).

thaigpt-next-125m at huggingface model: https://huggingface.co/wannaphong/thaigpt-next-125m

## License

>    Copyright 2021 Wannaphong Phatthiyaphaibun
>
>    Licensed under the Apache License, Version 2.0 (the "License");
>    you may not use this file except in compliance with the License.
>    You may obtain a copy of the License at
>
>        http://www.apache.org/licenses/LICENSE-2.0
>
>    Unless required by applicable law or agreed to in writing, software
>    distributed under the License is distributed on an "AS IS" BASIS,
>    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
>    See the License for the specific language governing permissions and
>    limitations under the License.

## Author

Wannaphong Phatthiyaphaibun