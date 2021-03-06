# Daisyworld-Ice-albedo
Codes in this repo has been written by Bharath Shankar and Eugene Gan.

The project was done in collaboration with Bei Yi Yang, Phee Yong Han and Wang Jingye.

Daisyworld is a modelling project in python for SP3175, under NUS Special Program in Science.



Daisyworld simulation is based on the Gaia hypothesis that James Lovelock created. Daisyworld is a computational simulation where we explore a simple Earth-like world that is only seeded by the two daisies: black daisies and white daisies. It uses the same theory as Energy Balance Model but also accounts for plants' growth and death and looks at their impacts on the planet's temperature.

One of the main issues with the Gaia hypothesis is that it only accounts for the equilibrium temperature at a 2D sphere. Hence to account for Earth being a 3D sphere, our group incorporated the ice-albedo model with Daisyworld, where each zone receives a different solar flux. Therefore, white and black daisies grow differently at different latitude zones over time. Each zone consists of a different equilibrium state even though all the zones are under the same luminosity (0.8) throughout the equilibrium period. 
Additionally, as life has persisted for over 3.8 billion years despite increasing luminosity, we increase the luminosity by 0.001 in our model after finishing the first iteration that reaches equilibrium for L=0.8. After the increase, we reset the whole daisy area coverage to get another set of different equilibrium states for each latitude zone's temperature and black and white daisies area coverage. The derivative of the luminosity will be the same until it reaches 1.8.

In our ice-albedo/Daisyworld model, we have got a few great insights. As L increases to a region between 1.3 and 1.65, the coverages of white and black daisies become more distinct in different latitude zones. This observation led us to discover "Oreoworld", where white daisies dominate near the equators, and black daisies dominate near the poles (Figure 1). Beyond L=1.65, there is a huge temperature spike; Even when Earth is too warm, white daisies are still growing at the poles, but eventually, at L=1.78, it will be inhabitable for any daisy.
