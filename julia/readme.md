Second week of april (probably thursday)

# Abstract

Julia is a rapidly growing programming language designed from the ground up to address the two language problem: users program in high level languages like Python or R while performant code is developed in Fortran or C.  Julia’s unique combination of a fast just-in-time compiler with a fresh multiple-dispatch programming paradigm makes it possible to effortlessly compose disparate code bases while achieving competitive performance. In this talk I will give an overview of the Julia programming language and demonstrate how this rapidly growing ecosystem will help you spend less time compiling so you can spend more time doing science. 


# Outline
1. Julia Overview
   - Julia REPL
   - Running Scripts
   - syntax
   - unicode characters in code 
   - multiple dispatch 
   - Loops are fast! 
2. Julia Package Ecosystem (Easy Reproducability)
   - Package Manager
   - Julia projects 
   - Precompilation and BinaryBuilder.jl
   - Auto Documentation 
   - Excellent documentation
3. Convenience Integrations 
   - Jupyter Notebooks 
   - Pluto Notebooks 
   - Ex: Intro To Computational Thinking Course
4. Scientific Computing 
   - DataFrames.jl
   - Plots.jl
   - DifferentialEquations.jl 
   - DynamicalSystems.jl 
   - Clima stuff
   - Multiple Dispatch Example: Unitful.jl, Measurements.jl
   - Optimizing your code via Benchmarks.jl @btime macro
   - Add link for julia-python-matlab cheatsheet
   
5. $\parial$P: Differentiable Programming 
6. Machine Learning in Julia
   - Flux.jl 
   - MLJ.jl
   - Feature importances with Shapely Values
   - DataFrames.jl (i.e. julia version of pandas)
   - Case study from our research
   
6. High Performance Computing 
   - Threads.@threads 
   - Loop optimizations with @inbounds, @simd,
   - Running on cluster (europa example)
   - Example with graphics cards? 
   
8. Resources
   - Julia Con videos
   - computational thinking course
   - Chris Rackauckas course 
