# Julia Life Cycle Model
Here I simulate a simple life cycle model in Julia. This is based on Matlab code from the course Dynamic Economics in Practice by Costa Dias and O'Dea. https://www.ifs.org.uk/publications/13801 Here I replicate models versions 1 and 5 from Costa Dias and O'Dea.

## Model v1
This program solves and simulates a finite period consumption and saving (cake-eating problem) problem. There is no income or uncertainty. The consumer starts with an endowment of assets and chooses how to allocate consumption over time. Solution is by value function iteration.

## Model v5
This version adds a realistic income stream with uncertainty. The household gradually accumulates assets to smooth consumption over income fluctuations and during retirement. 

# Setup
I think the easiest way to get up and running is with the free version of Julia Pro
* https://juliacomputing.com/products/juliapro.html

Other useful Julia resources include:
* https://en.wikibooks.org/wiki/Introducing_Julia
* https://juliadocs.github.io/Julia-Cheat-Sheet/
* https://docs.julialang.org/en/v1/
