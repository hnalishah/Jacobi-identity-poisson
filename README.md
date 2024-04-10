# Ckecking Jacobi Identity for bivectors 

A Poisson structure on an $n$-dimensional smooth manifold $M$ is defined by a $\mathbb{R}$-bilinear bracket  \{.,.\} on the space of smooth function on $M$, denoted by $C^\infty(M)$, which is anti-symmetric i.e. &#123;$f,g$ &#125;=-&#123;$g,f $&#125; for every $f,g\in C^\infty(M)$ and satisfies Leibniz's rule

<div style="text-align: center;"> &#123; $fg,h$ &#125; $=f$ &#123; $g,h$ &#125;$+g$ &#123; $f,h$ &#125;</div>

for every  $f,g,h\in C^\infty(M),$
and Jacobi identity


<div style="text-align: center;"> 
&#123;&#123;$f,g$&#125;$,h$&#125;+&#123;&#123;$g,h$&#125;$,f$&#125;+&#123;&#123;$h,f$&#125;$,g$&#125;$=0.$
</div>

The Leibniz's rule implies that for any $H\in C^\infty(M)$, the map $\{.,H\}: f\mapsto{f,H}$ is a derivation, i.e. a vector field on $C^\infty(M)$. This vector field is denoted by  $X_H$ and referred to as the **Hamiltonian vector field**  associated with $H$ on the Poisson manifold $M$. The, possibly singular, distribution generated by Hamiltonian vector fields is called  the {\em characteristic distribution} of the Poisson manifold $M$. As a consequence of Jacobi  identity this distribution integrates to a singular foliation. The equality  $\omega_{S_x}(X_f,X_h):=\{f,h\}$ defines a symplectic structure over leafs of this foliation and for this reason it is refereed to as symplectic foliation. The symplectic foliation completely determines the Poisson structure.



In a  given  coordinate  system $(U,x_1,..,x_n)$,  a Poisson bracket takes the form


\{f,g\}(x)=(d_x f)^t
\pi(x)d_x g=\sum_{i<j}\pi_{ij}(x)\left( \frac{\partial f}{\partial x_i}\frac{\partial g}{\partial x_j}-\frac{\partial f}{\partial x_j}\frac{\partial g}{\partial x_i}\right),

where  $\pi(x)$ denotes the skew symmetric matrix with components $\pi_{ij}(x)=\{x_i,x_j\}(x)$, and for every function $f$, we write 

d_x f=\begin{pmatrix}\frac{\partial f}{\partial x_1}(x)&\ldots&\frac{\partial f}{\partial x_n}(x)\end{pmatrix}^t\;.

In this setting, Jacobi identity translates to:

\begin{equation}
\sum_{l=1}^{n}  \frac{\partial\pi_{ij}}{\partial x_l}\pi_{lk}+\frac{\partial\pi_{jk}}{\partial x_l}\pi_{li}+\frac{\partial\pi_{ki}}{\partial x_l}\pi_{lj} =0\quad\quad \forall i,j,k\;,
\end{equation}

or equivalently 

$$
\{\{x_i,x_j\},x_k\}+\{\{x_j,x_k\},x_i\}+\{\{x_j,x_k\},x_j\}=0\quad\quad \forall i,j,k\;.
$$ (\#Jacobi Identity)


*To verify Jacobi identity locally, one may check condition \@ref(JacobiIdentity) in any given coordinate chart.*


One may introduce a Poisson structure through its associated bivector. We will adopt this approach. Any bivector $\pi$ naturally defines a linear bundle map, denoted $\pi$, from the cotangent space to the tangent space of the manifold $M$. The Hamiltonian vector field associated with a given function $H$ is defined by the equation

\begin{equation}
X_H=\pi\;\mathrm{d}H.
\end{equation}

It is evident that the characteristic distribution is the image of $\pi$. A function $f$ for which $X_f = \pi,\mathrm{d}f = 0$ is referred to as a Casimir.