# Tracking Light from Motion  
## A Visual Exploration of Charged Particle Radiation Using Python

This project visualizes radiation from an accelerating charged particle using Python. My main goal was to take one of the first big abstractions you run into in physics — electromagnetic radiation — and make it feel more intuitive.

A lot of the time in physics, you are handed an equation and expected to believe that it describes something real. I wanted this project to make the radiation pattern feel less like a static formula and more like something you can actually explore.

The idea was partly inspired by growing up near the Adler Planetarium. I always loved how their exhibits took huge scientific ideas and made them feel understandable by letting you interact with them. You were not just standing there observing the science; you were part of the process of understanding it. I wanted to bring a little bit of that feeling into this project.

## Physics Idea

An accelerating charge radiates electromagnetic energy. In the nonrelativistic dipole approximation, the angular radiation pattern follows

$$
I(\theta) \propto \sin^2\theta
$$

This means the radiation is strongest perpendicular to the direction of acceleration and weakest along the acceleration axis.

I also included the scaling

$$
I(\theta) \propto q^2 a^2 \sin^2\theta
$$

so the visualization shows how changing the charge or acceleration changes the overall strength of the radiation pattern.

## What This Project Includes

- 2D visualization of the dipole radiation pattern
- 3D surface plot of the angular radiation distribution
- Animated outward-moving wave model
- Interactive sliders for changing charge and acceleration

## Tools Used

- Python
- NumPy
- Matplotlib
- ipywidgets
- Jupyter Notebook

## Limitations

This project is a conceptual visualization, not a full solution to Maxwell’s equations. The dipole pattern and wave animation are simplified so the main idea is easier to see and interact with.
I also hope this helps me not just be a better student in the future, but also a better teacher.

## What I Learned

This project helped me connect the equations of electromagnetic radiation to their physical meaning.
