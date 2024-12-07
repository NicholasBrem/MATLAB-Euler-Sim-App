# Euler Sim App

App is a visualisation and attitude parameter conversion tool for specific attitude status:

𝜓 = 10cos(0.01𝑡), 𝜃 = 30sin(0.02𝑡), 𝜙 = 20sin(0.01𝑡)

User inputs a time range and app displays the orientation of the object at the current time on a 3D
plot as the user operates the slider. Euler Angles are in a 3-2-1 sequence. Orientation is updated
dynamically.

App also displays the Rotation Matrix, Quaternions, Classical and Modified Rodrigues Parameters,
Cayley-Klein Matrix and w-z Parameters at current time.

Plot data function plots a graph of each parameter vs time, allowing singularities to be identified
and displaying the adequacy of each parameter at displaying the above status.