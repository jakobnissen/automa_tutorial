# Automa tutorial

__Currently only part 1 is released. Part 2 will be created on a later date,
and will be about how to create BioJulia readers and writers using Automa.__

[Automa.jl](https://github.com/BioJulia/Automa.jl) is a Julia package that creates
optimized finite state machines (FSMs) from regular expressions. These finite state
machines may be augmented with *actions*, which enables the FSM to execute arbitrary
Julia expressions during the execution of the FSM.

In plain words, Automa can be used to generate fast and accurate parsers.

In this short tutorial, I introduce how to use Automa to parse data stored in
memory.
