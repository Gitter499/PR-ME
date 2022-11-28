https://www.cs.cmu.edu/~motionplanning/lecture/Chap8-Kalman-Mapping_howie.pdf

d D. Fox
Finding the correction (no noise!)
y = Hx
Ω = {x | Hx = y} HH Kν =ν T substituting yields x H Kν T Δ = Ω = {x | Hx = y} Δx
we require
x
ˆ(k +1| k) • ⇒ HΔx = y − Hxˆ(k +1| k) = H(x − xˆ(k +1| k)) =ν
H(xˆ(k +1| k) + Δx) = y
is the "best" estimate of .
G
