## Hi, I'm Axel

Second-year Computer Engineering student at UIB, in Mallorca. I write C++,
mostly because I want to understand what happens underneath — memory layout,
what the compiler actually emits, where the time goes. Low-level systems and
performance are where I want to end up.

I learn by building things that are slightly harder than what I know how to do,
and by reading the standard library when I get stuck.

### What I'm working on

**[FunctionParser](https://github.com/MrAxelius/FunctionParser)** — a C++20
library for parsing and evaluating mathematical expressions. Hand-written lexer
with positioned errors, shunting-yard parser building an AST, recursive
evaluator, and sampling over a range. Public API behind a pImpl facade,
versioned with an inline namespace, tested with Catch2.

**[Function-render](https://github.com/MrAxelius/Function-render)** — a function
viewer built on SFML, and the reason FunctionParser exists. 2D plotting and a 3D
surface pipeline with my own vector and matrix types, because writing the
projection math myself was the point.

### Currently
Learning where my code breaks by writing the tests I'd rather not write.
