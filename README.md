# Mole - The M0 Overlay Language

This repo contains the beginnings of Mole, a new Parrot language which is being
designed to generate the very low-level M0 langauge.

# What is important about Mole?

Mole is the future of Parrot. The point of Mole is to provide a medium-level
language which will be comfortable for Parrot developers to code in. In the
future, instead of writing Parrot internals in C, Mole will be used, which will
be compiled down to M0 and then M0 bytecode. This will allow the amount of C
that is in Parrot to greatly contract, which means crossing language barriers
will be much less common and thus allow many optimization techniques to be
applicable.

# Why?

M0 is extremely low-level, and was never intended to be written by humans
except during the bootstrapping phase. M0 was created because Parrot wants to
implement an efficient JIT compiler, which is currently not possible do to the
way Parrot internals (all the C code) are implemented.

M0 consists of roughtly 40 opcodes from which the rest of Parrot can be built
from.  Currently Parrot has over 1000 opcodes (due to supporting various
combinations of argument types), which basically precludes the possiblity of
implementing an efficient and maintainable JIT.

# What does Mole look like yet?

We don't yet know. It is currently in the design phase.
