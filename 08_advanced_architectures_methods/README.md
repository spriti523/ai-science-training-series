# Advanced AI Architectures and Methods

AI-Driven Science on Supercomputers @ ALCF 2022

**Contact:** Venkat Vishwanath ([venkat@anl.gov](mailto:///venkat@anl.gov)), Bethany Lusch ([blusch@anl.gov](mailto:///blusch@anl.gov)), Carlo Graziani ([cgraziani@anl.gov](mailto:///cgraziani@anl.gov)) 


[AI Accelerators for Science](https://github.com/argonne-lcf/ai-science-training-series/blob/main/08_advanced_architectures_methods/ALCF_AI_Testbed_Vishwanath.pdf)
    
[Gaussian Process Modeling](Gaussian_Process_Modeling.ipynb)

[Advanced AI Methods](https://github.com/argonne-lcf/ai-science-training-series/blob/main/08_advanced_architectures_methods/AITrainingSeries-AdvancedMethods.pdf)

**Useful Links**

 [Getting started on AI Testbed](https://www.alcf.anl.gov/support/ai-testbed-userdocs/index.html)
 
 [Useful AI Testbed Resources](https://github.com/argonne-lcf/AIaccelerators-SC22-tutorial)
 
 **Homework**
 
 Submit a paragraph about: 
 
- How could you use AI for a problem that interests you? 
- What is the task? 
- What kind of data would you use? 
- What kind of method or model might be appropriate? 
- What kind of metric would you use to measure success? 

Feel free to consult the Internet for ideas.

This paragraph can be placed in a README in git and you can submit the link. 

- How could you use AI for a problem that interests you? 
AI is a sophisticated way of using machine learning algorithms, or applying statistical and computational algorithms to ginormous data sets. I am a computational chemist by training, and when it comes to applying innovative methods or techniques, I look into improving first-principles methods, drug discovery, reaction prediction, drug action prediction, and quantum computing.
- What is the task? 

The task, in the above mentioned cases:
1) Computational Chemistry: In post-Hartree Fock methods or first-principles MD simulations, there are repeated calculations of certain quantities such as dielectric matrices or other giant matrices. I am extremely tempted to machine-learn such objects so that the post-HF methods become computationally fast.
2) In pharmaceuticals, I have been working with many graph-based methods for structure predictions of toxic molecules. I believe with AI, and its capacitance, we can circumvent the issue of getting accurate molecules by using exact matrices and not hashing them to a confined dimension. Although we need to work on the methods that can facilitate such a vision. 
3) Quantum Computing: Despite the fact that quantum computers are largely noisy, quantum machine learning is an emerging field. And I am tempted to contribute towards the development of algorithms that can scale well with AI methods.

- What kind of data would you use?
As mentioned above, dielectric matrix, electronic charge, displacements. Molecules with similar properties.

- What kind of method or model might be appropriate? 
Method, I feel in terms of models, GPR is the method that would be suited. It is just a guess, since, for many of the problems discussed I believe it will be easier to get a better prior . 

- What kind of metric would you use to measure success? 
I think keeping simple metric would be helpful, for example. Mean absolute error.