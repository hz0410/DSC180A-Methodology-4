---
layout: default
---

# About Me

**Name:** Haowen Zhang
**UCSD Email:** haz099@ucsd.edu
**Section:** Steering of Diffusion Model (D32)
**Mentor:** Yusu Wang

## Quarter 2 Project Reflections

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in my domain this quarter is the project1 checkpoint. We were asked to observe how the models perform on the MNIST and CIFAR-10 dataset with different parameters. 

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate whether changing classifier-free guidance strength during sampling can improve the balance between class accuracy, image quality and diversity. I may use a non fixed guidance weight to test. 

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

The evaluation may be strengthened by repeating each guidance experiment with multiple random seeds and report the variation in the results. Also, examine results separately for each classes can test whether some classes may perform poorly. 

**4. What other techniques would you be interested in using in your project?**

I am interested in comparing sampling methods such as the Euler and Heun to examine how they interact with guidance strength. I am also interested in exploring precision and recall metrics for generative models to help distinguish whetehr stonger guidance improves sample quality att he expense of covering less of the real data distribution. 