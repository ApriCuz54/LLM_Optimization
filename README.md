# LLM_Optimization
This Repo constains all the work I have done using Large Language Models

- LLM_arch.pdf contains a basic presentation I gave to my professor, introducing LLM Architecture.
- LLM_Reqs.pdf contains another presentation I gave discussing the limits when running LLMs (memory and computation bound). This goes into detail on the different stages of an LLM (prefill, decode), and also goes into some detail of using Roofline Models.

## Sparse Low Rank Activation 
 - LoRA directory

The goal of this project was to simplify and speed up the process of fine-tuning large language models (LLMs), so that more people, even those without powerful computing resources, can adapt these models to their own specific tasks. By making this process more efficient, the aim was to help researchers and developers easily customize LLMs for real-world applications without needing high-end hardware. My approach was to explore ways to reduce the computational burden of fine-tuning while maintaining high accuracy, focusing on optimizing the LoRA (Low-Rank Adaptation) method.
 
I implemented LoRA with the Lottery Ticket Hypothesis, which reduced the number of parameters needed for fine-tuning large language models.

## Testing Computation and Memory Bounds
This a recently started project, where I aimed to find the computation/memory bounds while running LLMs (inference, training, fine-tuning) and figure out if there is a way to allieviate that. 

I have been testing different methods of fine-tuning to see the efficiency of these methods. (Testing_bounds/RoBERTa_ft)