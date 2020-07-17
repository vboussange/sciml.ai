@def rss_pubdate = Date(2020,7,20)
@def rss = """ SciML Ecosystem Update: SDE Adjoints, FFORD Layers, and Jump Diffusion"""
@def published = " 20 July 2020 "
@def title = " SciML Ecosystem Update: SDE Adjoints, FFORD Layers, and Jump Diffusion"
@def authors = """<a href="https://github.com/ChrisRackauckas">Chris Rackauckas</a>"""  

## Adaptive Post-Leap Tau Leaping

## Jump Diffusion Euler-Maruyama and Implicit Euler-Maruyama

## Adjoints of Stochastic Differential Equations

https://frankschae.github.io/post/gsoc2020-high-weak-order-solvers-sde-adjoints/

## Continuous Normalizing Flows and FFJORD Layers

## Sparse Matrix Support in ODE/SDE/DAE Adjoints

# Next Directions: Google Summer of Code

The next directions are going to be highly tied to the directions that
we are going with the latest Google Summer of Code, so here are a few
things to look forward to:

- Some tooling for automated training of physics-informed neural
  networks (PINNs) from ModelingToolkit symbolic descriptions of the
  PDE.
- Efficiency enhancements to native Julia BDF methods.
- More Lie Group integrator methods.
- Higher efficiency low-storage Runge-Kutta methods with a demonstration
  of optimality in a large-scale climate model (!!!).
- More high weak order methods for SDEs
- Causal components in ModelingToolkit

And many many more. There will be enough that I don't think we will
wait a whole month for the next update, so see you soon!