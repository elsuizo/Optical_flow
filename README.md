<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

Optical_flow
============

##implementations of optical flow algorithms 

Horn and Schunck algorithm

Assumptions:
Brightness constancy

$$ f(x,y,t) = f(x+dx,y+dy,t+dt) $$

if expand the Taylor series of $f(x,y,t)$ we obtain:

$$f(x,y,t) = f(x,y,t) + \frac{\partial f(x+dx-x)}{\partial x}+\frac{\partial f(y+dy-y)}{\partial y} +\frac{\partial f(t+dt-t)}{\partial t} $$

$$0 = f_{x}dx + f_{y}dy + f_{t}dt$$

$$0 =  f_{x}\frac{dx}{dt} + f_{y}\frac{dy}{dt} + f_{t}\frac{dt}{dt}$$

$$0 = $ f_{x}u + f_{y}v + f_{t}$$



