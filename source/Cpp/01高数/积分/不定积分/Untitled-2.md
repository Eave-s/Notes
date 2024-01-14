
$\displaystyle一质量为m，体积为B的小球从水面开始因重力下沉,水的密度为\rho ,阻力\\与速度成正比，比例系数为k,外力=重力-浮力-阻力,速度v=v(t),\\位移y=y(t).$
$\displaystyle（1）求 v与y的关系式$
$\displaystyle（2）求y=y(v)$
>$答案：$
（1）$$v=\frac{dy}{dt}$$
$$a=\frac{dv}{dt}=\frac{dv}{dy}\frac{dy}{dt}=v\frac{dv}{dy}$$
$$\color{red}{}mv\frac{dv}{dy}=mg-\rho gB-kv$$
（2）
$$\frac{mv}{mg-\rho gB-kv}dv=dy\,\,\,\,\,\,\,\,\,\,且y=0时，v=0$$
$$\int_0^y dy=\int_0^v\frac{mv}{mg-\rho gB-kv}dv$$
$$\int_0^y dy=\int_0^v -\frac{m}{k}(\frac{-kv+mg-\rho gB -(mg-\rho gB)}{mg-\rho gB-kv})dv$$
$$\int_0^y dy=-\frac{m}{k}\int_0^v (1-\frac{mg-\rho gB}{mg-\rho gB-kv})dv$$
$$\int_0^y dy=-\frac{m}{k}(\int_0^v dv-\int_0^v \frac{mg-\rho gB}{mg-\rho gB-kv}dv)$$
$$\int_0^y dy=-\frac{m}{k}(\int_0^v dv+\frac{1}{k}\int_0^v \frac{mg-\rho gB}{mg-\rho gB-kv}d(mg-\rho gB-kv))$$
$$y=-\frac{m}{k}(v+\frac{mg-\rho gB}{k}ln(mg-\rho gB-kv))|_0^v$$
$$y=-\frac{m}{k}(v+\frac{mg-\rho gB}{k}ln(\frac{mg-\rho gB-kv}{mg-\rho gB}))$$
$$\color{red}{}y=-\frac{m}{k}(v+\frac{mg-\rho gB}{k}ln(1-\frac{kv}{mg-\rho gB}))$$