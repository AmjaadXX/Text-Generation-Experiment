# Text-Generation-Experiment
This project is an experiment to explore how different AI text generation settings affect model output. It compares two Hugging Face models (GPT-2 and DistilGPT-2) and three decoding strategies: Greedy, Top-K, and Top-P.
The goal is to understand how small changes in generation configuration can significantly impact the quality, creativity, and stability of AI-generated text.

##  Models Used

- GPT-2  
- DistilGPT-2  

##  Decoding Strategies

- **Greedy Decoding** → selects the most probable next word (can be repetitive)  
- **Top-K Sampling** → selects from the top K most likely words (more balanced)  
- **Top-P (Nucleus Sampling)** → selects from a probability mass (more creative but less stable)  

##  Key Observations

- Greedy decoding tends to produce repetitive and rigid text  
- Top-K provides more coherent and stable results  
- Top-P increases creativity but may reduce structure  
- GPT-2 generates more structured outputs  
- DistilGPT-2 is faster but slightly less stable  

##  Interface

A Gradio interface is used to:
- Select a model (GPT-2 or DistilGPT-2)  
- Choose a decoding strategy  
- Generate and view outputs in real time  

##  Goal

To better understand how decoding strategies influence language model behavior and output quality.

##  Technologies Used

- Python  
- Hugging Face Transformers  
- Gradio  

## 📌 Author

Built as a small AI experimentation project to explore NLP generation behavior.
