

$$W(\mu_1,\mu_2):=\inf_{j \in \Lambda}\int\!\int j(s_1,s_2) d(s_1,s_2)ds_2\ ds_1 $$
$$W(\mu_1,\mu_2)=\sup_{f:K_{d,d_{\mathbb{R}}}(f)\leq 1}\int\! \big(\mu_{1}(s)-\mu_{2}(s)\big)f(s)ds\$$

$$l(T, \hat{T})(s, a)
    &=&\!\gamma\!\int\!\big( T(s'|s,a)\!-\!\hat{T}(s'|s,a)\big) v(s')ds'
    $$

$$l(T, \hat{T})(s, a) &\leq& \gamma ||T(s'|s,a)-\hat{T}(s'|s,a)||_{1}||v||_{\infty}$$


$$||T(\cdot|s,a)-\hat{T}(\cdot|s,a)||_{1}\leq \sqrt{2KL\big(T(\cdot|s,a)||\hat{T}(\cdot|s,a)\big)}\ $$

$$L\big(T,\widehat T\big)(s,a)=\Big(C\ W\big(T(\cdot|s,a),\widehat T(\cdot|s,a)\big)\Big)^2\ .$$
This highlights a nice property of Wasserstein, namely that minimizing this metric yields a value-aware model.
