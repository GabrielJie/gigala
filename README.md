# Engineering Design by Artificial Intelligence

Are you interested in the new ways of engineering design? This repository is an attempt to apply artificial intelligence algorithms for the purpose of engineering design of electrical and structural elements and components. I combine numerical simulation like finite element analysis with artificial intelligence like reinforcement learning and genetic algorithms to produce optimal designs. In fact, to the best of my knowledge, I was the first who started using combination of RL and FEA for the purpose of structural engineering design in 2018. Recently, my work has been focused on the analysis of dynamics of offshore structures, electrical circuits and topology optimization. I am constantly exploring different ways that AI can be applied to science and engineering. With my diverse interests, I am using this repository as a testbed for my ideas. I hope that my work can inspire you to explore the different ways that artificial intelligence can be applied to your field.
 
 
Please check my [blog](https://gigatskhondia.medium.com/) and [manuals](https://gigatskhondia.github.io/gigala/) for the specifics of the models and algorithms I use:

* [Engineering Design by Reinforcement Learning and Finite Element Methods.](https://gigatskhondia.medium.com/engineering-design-by-reinforcement-learning-and-finite-element-methods-82eb57796424)
* [Engineering Design by Genetic Algorithms and Finite Element Methods.](https://gigatskhondia.medium.com/engineering-design-by-genetic-algorithms-and-finite-element-methods-5077ebadd16e)
* [On artificial intelligence aided engineering design.](https://gigatskhondia.medium.com/on-artificial-intelligence-aided-engineering-design-a6cf6f76b3d9)
* [Some ideas on using reinforcement learning in marine construction and sustainable energy development.](https://gigatskhondia.medium.com/using-reinforcement-learning-in-marine-construction-and-sustainable-energy-development-b5f301fb2397)
* [Modelling offshore pipelaying dynamics.](https://medium.com/@gigatskhondia/modelling-pipelay-dynamics-with-second-order-ordinary-differential-equation-using-python-4d6fc24055b)
* [Modelling offshore pipelaying dynamics - Part 2.](https://gigatskhondia.medium.com/modelling-offshore-pipelaying-dynamics-part-2-in-6-dof-a360965a7a89)
* [Pipelay vessel design optimisation using genetic algorithms.](https://medium.com/@gigatskhondia/pipelay-vessel-design-optimisation-using-genetic-algorithms-506aa04212f1)
* [Python and Finite Element Methods: A Match Made in Heaven?](https://gigatskhondia.medium.com/python-and-finite-element-methods-a-match-made-in-heaven-ee2ed7ca14ee)


Design of bionic partition: 

<img width="342" alt="Screenshot 2023-06-29 at 15 56 49" src="https://github.com/gigatskhondia/gigala/assets/31343916/54689109-65ec-4b4c-87ae-1fe11dba031c">


#### Latest ideas: ####
On how to apply recent developments in Generative AI to my solution: you can feed an image to chatGPT and ask it questions about this image. For example, you can ask 'do you like this image?'. In case of designing a structure like a bridge, you can ask 'do you like this design of a bridge?'. Based on chatGPT's answer you can calculate a sentiment score. You can feed this sentiment score to your RL agent as additional reward (making it huge). You do not have to ask chatGPT every MDP iteration step, just once in a while.

<img width="568" alt="Screenshot 2023-05-16 at 11 37 50" src="https://github.com/gigatskhondia/gigala/assets/31343916/ef983d4e-e8f6-456e-80b9-d2fa95aba1d8">

#### TODO: ####
* Validate robotic and PDE pipe models
* Imporve sizing models 
  *  Do not need to remesh, just set stiffness to a small number for absent elements 
  *  Use different objective, e.g. compliance
  *  Use CNN for features ?
  *  Apply RL training metrics
  *  Test generalizability
*  Revive Alpha and MCTS models, utilize AlphaDev
*  Update manuals
*  Design MEMS
   *  Use SfePy for FEM ?
   *  Use GNN for features ?
   *  Test generalizability

To keep up to date with the project please check [Gigala](https://gigala.io/) page.

#### How to support: ####
* Star this project
* [Sponsor](https://www.paypal.me/gigatskhondia) this project 
* [Contact](https://gigala.io/) me if you are interested in investing in my research or adapting my solutions to your project
