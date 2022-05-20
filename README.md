# Introduction to Network Models
## InFoMM CDT IEP - April 2021 and March 2022

The study of network models began with Euler and the
problem of the seven bridges of Konigsberg. Since then
the field has grown tremendously and finds applications
in a many fields including communications, epidimeology, 
chemistry, biology,material science, and social studies 
to name a few.

This repository holds code from a 1-day workshop conducted 
as a part of the Industrially Focused Mathematical Modeling
CDT's program and is intended to serve as an introduction 
to network models. Our goal here is not to go deep into the
mathematics of the subject, but rather provide guidance
on how to get started with developing a network model, 
implementing it in code, running simulations, and 
calculating physical quantities of interest from the 
simulation trajectories. We will be using examples primarily 
from chemical engineering and materials science.

## Literature references
Please refer to the following articles to dive deeper into the subject


1. Albert, R.; Barabasi, A.-L. Statistical Mechanics of Complex Networks. Rev. Mod. Phys. 2002, 74 (1), 47–97. https://doi.org/10.1103/RevModPhys.74.47.

2. Andrade, J. S.; Araújo, A. D.; Buldyrev, S. V.; Havlin, S.; Stanley, H. E. Dynamics of Viscous Penetration in Percolation Porous Media. Phys. Rev. E 2001, 63 (5), 051403. https://doi.org/10.1103/PhysRevE.63.051403.

3. Andrade Jr., J. S.; Street, D. A.; Shibusa, Y.; Havlin, S.; Stanley, H. E. Diffusion and Reaction in Percolating Pore Networks. Phys. Rev. E 1997, 55 (1), 772–777. https://doi.org/10.1103/PhysRevE.55.772.

4. Baeza, G. P.; Dessi, C.; Costanzo, S.; Zhao, D.; Gong, S.; Alegria, A.; Colby, R. H.; Rubinstein, M.; Vlassopoulos, D.; Kumar, S. K. Network Dynamics in Nanofilled Polymers. Nat Commun 2016, 7 (1), 11368. https://doi.org/10.1038/ncomms11368.

5. Girvan, M.; Newman, M. E. J. Community Structure in Social and Biological Networks. Proceedings of the National Academy of Sciences 2002, 99 (12), 7821–7826. https://doi.org/10.1073/pnas.122653799.

6. Gostick, J. T. Versatile and Efficient Pore Network Extraction Method Using Marker-Based Watershed Segmentation. Phys. Rev. E 2017, 96 (2), 023307. https://doi.org/10.1103/PhysRevE.96.023307.

7. Katifori, E. The Transport Network of a Leaf. Comptes Rendus Physique 2018, 19 (4), 244–252. https://doi.org/10.1016/j.crhy.2018.10.007.

8. Newman, M. E. J. The Structure and Function of Complex Networks. SIAM Rev. 2003, 45 (2), 167–256. https://doi.org/10.1137/S003614450342480.

9. Newman, M. E. J.; Watts, D. J.; Strogatz, S. H. Random Graph Models of Social Networks. Proceedings of the National Academy of Sciences 2002, 99 (Supplement 1), 2566–2572. https://doi.org/10.1073/pnas.012582999.

10. Stanley, H. E.; Andrade, J. S.; Havlin, S.; Makse, H. A.; Suki, B. Percolation Phenomena: A Broad-Brush Introduction with Some Recent Applications to Porous Media, Liquid Water, and City Growth. Physica A: Statistical Mechanics and its Applications 1999, 266 (1–4), 5–16. https://doi.org/10.1016/S0378-4371(99)00029-1.

11. Strogatz, S. H. Exploring Complex Networks. Nature 2001, 410 (6825), 268–276. https://doi.org/10.1038/35065725.


12. Watts, D. J.; Strogatz, S. H. Collective Dynamics of ‘Small-World’ Networks. 1998, 393, 3.



## Schedule for the workshop

| Time slot    | Topic                                            |
|--------------|--------------------------------------------------|
|09:00 - 09:30 | Introductions and some minor preparation         |
|09:30 - 11:00 | Examples of network models in porous media       |
|11:00 - 11:30 | Coffee break                                     |
|11:30 - 13:00 | Implementing network models I (working session)  |
|13:00 - 14:00 | Lunch                                            |
|14:00 - 15:30 | Implementing network models II (working session) | 
|15:30 - 16:00 | Tea                                              |
|16:00 - 17:00 | Open discussion time**                           |


>>> 
** If there are any requests for specific topics, please let media
   know and I can prepare
>>>

## Preparation
This will be a hands on workshop where we will have two big sessions
to implement some example models. We will be using Python as our 
programming language of choice. You will need a python environment with
the following packages installed

* numpy
* scipy
* matplotlib
* [networkx](https://networkx.org/)
* [openpnm](http://openpnm.org/)

## Notes
* All code presented is for illustration purpose only. It is not optimized to
  run on large system sizes.

* In case of any questions/issues please reach out.