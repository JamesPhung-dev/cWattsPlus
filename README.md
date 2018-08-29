# cWatts+
cWatts+ is a prototype lightweight software-based virtual power meter. Utilizing a simple but powerful application-agnostic power model, it offers comparable performance to existing but more complex power models. It uses a small number of widely available CPU event counters and the Performance Application Programming Interface Library to estimate power usage on a per-thread basis. It has minimal overhead and is portable across a variety of systems. It can be used in containerized or virtualized environments. We evaluate the estimation performance of cWatts+ for a variety of real-world benchmarks that are relevant to large distributed systems.

This work was presented at CCGRID 2017. The paper can be found here: https://doi.org/10.1109/CCGRID.2017.100.
