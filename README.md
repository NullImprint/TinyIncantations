# TinyIncantations [alpaca]
400 examples to teach language models to write tiny, medium, and long incantations that (mostly) rhyme.
Produced with distilabel. The default context in this dataset is fiction, so at higher learning rates, 
the model will likely suggest how incantations can be added in to a story, or etc. 
best results were had with gemma-2-2b-it abliterated trained for 3e at an lr of 2e-5 with a rank and alpha of 16 with rank stabilization. 
