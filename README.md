# GePpeTto

[GePpeTto](https://arxiv.org/abs/2004.14253), is a generative language model for Italian, built using the [GPT-2 architecture](https://github.com/openai/gpt-2).

You can find further details in the paper:

Lorenzo De Mattei, Michele Cafagna, Felice Dell’Orletta, Malvina Nissim, Marco Guerini "GePpeTto Carves Italian into a Language Model", arXiv preprint. Pdf available at: https://arxiv.org/abs/2004.14253

Usage
=====

[Download](https://drive.google.com/file/d/1suAiO1LO35aZArZODnYZY_be-rTZHZkC/view?usp=sharing) GePpeTto checkpoint.

You can uncompress the model folder and load the model using [hugging face GPT-2 implementation](https://huggingface.co/transformers/model_doc/gpt2.html).

For usage example check out [hugging face run generation example](https://github.com/huggingface/transformers/blob/master/examples/run_generation.py).

For fine tuning example check out [hugging face run language modelling example](https://github.com/huggingface/transformers/blob/master/examples/run_language_modeling.py).

Citation
========

Please use the following bibtex entry:

```
@misc{mattei2020geppetto,
    title={GePpeTto Carves Italian into a Language Model},
    author={Lorenzo De Mattei and Michele Cafagna and Felice Dell'Orletta and Malvina Nissim and Marco Guerini},
    year={2020},
    eprint={2004.14253},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
