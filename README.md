O4636 LANL contribution to ryujin
======

[Ryujin[(https://github.com/conservation-laws/ryujin) is a high-performance high-order collocation-type 
finite-element
solver for conservation equations such as the compressible Navier-Stokes
and Euler equations of gas dynamics. The solver is based on the [convex
limiting technique](https://doi.org/10.1137/17M1149961) to ensure
[invariant domain preservation](https://doi.org/10.1137/16M1074291) and
uses the finite element library [deal.II](https://github.com/dealii/dealii)
([website](https://www.dealii.org)) and the [vector class SIMD
library](https://github.com/vectorclass/version2). As such the solver
maintains important physical invariants and is guaranteed to be stable
without the use of ad-hoc tuning parameters.


LANL Copyright Statement
------------------------

Copyright (c) 2023 - 2023 by Triad National Security, LLC

All rights reserved.

This program was produced under U.S. Government contract 89233218CNA000001
for Los Alamos National Laboratory (LANL), which is operated by Triad
National Security, LLC for the U.S. Department of Energy/National Nuclear
Security Administration. All rights in the program are. reserved by Triad
National Security, LLC, and the U.S. Department of Energy/National Nuclear
Security Administration. The Government is granted for itself and others
acting on its behalf a nonexclusive, paid-up, irrevocable worldwide license
in this material to reproduce, prepare. derivative works, distribute copies
to the public, perform publicly and display publicly, and to permit. others
to do so.

This program is Open-Source under the BSD 3-clause License.


BSD 3-clause License
--------------------

Copyright (c) 2020 - 2023 by the ryujin authors

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 - Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
 - Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 - Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
