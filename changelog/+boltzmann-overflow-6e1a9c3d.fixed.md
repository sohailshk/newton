Fix `newton.math.boltzmann` returning NaN when `alpha * a` and `alpha * b` are large in magnitude, which overflowed or underflowed `exp`.
