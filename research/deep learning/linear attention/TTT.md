Code: [ttt-lm-pytorch/ttt.py at main · test-time-training/ttt-lm-pytorch](https://github.com/test-time-training/ttt-lm-pytorch/blob/main/ttt.py)
![[Pasted image 20250203145923.png]]
## Output rule
$$
z_t=f(x_t;W_t)
$$
## Update rule
$$
W_t =W_{t−1}−η∇ℓ(W{t−1};x_t)
$$
$$
\ell(W; x_t) = \| f(\tilde{x}_t; W) - x_t \|^2
$$
