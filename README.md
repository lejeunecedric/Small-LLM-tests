# Small models on small machines

Here we look into using small models for everyday tasks, and see how they perform for different uses on different configurations.

## Machines

I use 3 configurations : 

* Linux Mint on [Dell Precision Laptop 7520](https://devicebeast.com/laptops/dell-precision-15-7520),  16 GB RAM, Intel i7 and Quadro M2200 4GB VRAM

* Win 11 on [Acelogic F3A](https://acemagic.com/products/acemagic-f3a-mini-pc?variant=49768526512434), 32 GB RAM, AMD Ryzen AI 9 HX370

* Win 11 on [Lenovo  ThinkBook 14s Yoga](https://www.lenovo.com/us/outletus/en/p/laptops/thinkbook/thinkbook-yoga/thinkbook-14s-yoga/20wex013us), 16 GB RAM, Intel i7

## Inference managers

This is an interesting topic, that has a significant impact on performances and what can actually be done. Those tools are graphical interfaces sitting on top of actual inference engines and giving access to some parameters. They all have their pros and cons.

* LM Studio :
https://www.lmstudio.com

  very user-friendly, a lot of tweaking parameters available directly in the GUI but limited format support. Direct access to Hugging Face download and very complete client and 

* Lemonade :
https://lemonade-server.ai/

limited tweakability in the GUI, but comes with AMD Ryzen specific models and directly integrated in N8N workflows

* vLLM :
https://lemonade-server.ai/

has both NVidia and AMD optimisations, now also has a web GUI to tweak parameters

## Models

There’s quite a lot of litterature about engines, quantization and optimization. I’m still in the learning process and it’s pretty deep. 

* Resources

Great list of LLMs and tools for local processing https://github.com/rafska/awesome-local-llm
There is some good info about AMD Ryzen MAX / Strix Halo here : https://strixhalo.wiki/
