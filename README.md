Hi team

i thought we can use the readme to organize the different tasks people are working on or as progress tracker to see what needs to be done. 

if you read this, add your favorite greek letter. 

$\xi$ (Mo)

$\psi$ (John)

$\ dont have one (Alaina)

-------------------------------------------------------------
| task item | progress note | completed (Y/N)|
------------|----------------|--------------|
| learn what is pendulum      |      play with 2D example          |     Y    |
|   generalize to 3D     |    defined Lagrangian; solve numerically in Julia          |         Y     |
|      animate in 3D      |        use numeric solution to make plot        |      Y        |
|      add decay  |      introduce non-conservative forces (dampening) into Lagrange         |      Y        |
-------------------------------------------------------------

Final Remarks:
Alaina - I am looking at both the slow and fast pendulum solutions and it looks like they both dampen at the same rate even though they are oscillating at different rates.
This reminds me of the [Brachistochrone lecture](https://cooperrc.github.io/dynamics/tutorials/03_brachistochrone) where the balls placed at different locations on the curve (with no other forces acting on them) reached the bottom at the same time.
I looked into this phenomenom and found that the final equation for linear damped oscillator is θ(t)=e^−γt(Acos(ωt)+Bsin(ωt)) where γ=c/2mL^2 and c is some dampening constant. This shows that, regardless of frequency, the damping term will only impact the decay rate and not the oscillation frequency of the pendulum.
This is shown on our angle vs time graph, where the magnitude is stuck between two boundary limits. I would be interested to explore what would need to happen for the two boundary limits to not be equal in magnitude (i.e. 0.5 and -0.3 instead of 0.5 and -0.5).
