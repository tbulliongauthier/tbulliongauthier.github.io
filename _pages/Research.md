---
permalink: /research/
name : "Research" 
author_profile : false
classes: nosidebar

---
Here is quick description of my research topics.


**Affine Sobolev inequalities**

Zhang proved the affine Sobolev inequality


$$
||f||_{L^{N/(N-1)}}\\ \leq C_{1,p} \left( \int_{\mathbb{S}^{N-1}} ||\nabla f \cdot \xi ||_{L^1}^{-N} \ d\xi \right)^{-1/N}, \ \forall \  f \in W^{1,1}. \ \text{(1)} 
$$ 


This inequality is a refinement of the classical Sobolev inequality and it is invariant under unimodular transformations. 

The work of Zhang inspired many subsequent results. For example, Haddad and Ludwig established the following fractional counterparts of (1) 


$$  ||f||_{L^{Np/(N-sp)}} \leq C_{s,p} \mathcal{E}_{s,p}(f) : = \left(\int_{\mathbb{S}^{N-1}} \left(\int_{0}^{\infty} t^{-sp} || \Delta^{\lfloor s \rfloor +1}_{t\xi} f ||_{L^p}^p\ dt  \right)^{-N/sp} \ d\xi \right)^{-s/N},$$  


when \\(sp<N \\).

I proved higher-order counterparts of the above inequalities, for example

$$ ||f||_{L^{Np/(N-sp)}} \leq C_{s,p}  \left(\int_{\mathbb{S}^{N-1}} ||\partial^s_{\xi} f ||_{L^p}^{-N/s} \ d\xi \right)^{-s/N}, $$


when \\( s\\) is an integer, \\(1<p<\infty\\) and \\( sp<N \\). 
The rearrangement and convex geometry tools that were used in previous contributions do not seem to have counterparts for higher-order inequalities. We need to rely on the existence of optimal unimodular transformations and slicing inequalities. While these tools do not yield sharp estimates, they are robust and lead to various affine inequalities. For example, they allow us to generalize the reverse affine inequalities of Haddad, Jimenez, and Montenegro and obtain the "optimal" reverse inequalities


$$||f||_{L^p}^{1-1/N} |f|_{W^{s,p}}^{1/N} \leq C_{s,p} \mathcal{E}_{s,p}(f)$$


for each \\(s>0\) and \\(1\leq p<\infty\\), except possibly when \\( s\geq 2\\) is an integer and \\(p=1\\).


**Anistropic interaction energies**
The study of minimizers of interaction energies of the form 


$$
\mathcal{P}(\mathbb{R}^N) \ni \nu \mapsto \mathcal{E}(\nu)= \int_{\mathbb{R}^N} \int_{\mathbb{R}^N} W(x-y) d\nu(x) d\nu(y) + \int_{\mathbb{R}^N} V(x) \ d\nu, 
$$

where \\(W\\) is the Coulomb kernel, is a classical topic. Recently, motivated by applications in the physics of materials,  Mora, Rondi, Scardia, and collaborators, started to study the minimizers of anisotropic interaction functionals when \\( W(x)= \frac{\Psi(x/|x|)}{|x|^{N-2}}\\) is not radial. They proved that, when the Fourier transform \\(W \\) is stricly positive and \\( V(x)=|x|^2 \\), the minimizer of \\(\mathcal{E}\\) is the normalized characteristic function of an ellipsoid. 

Inspired by this result, we prove that, when \\(W\\) and its Fourier transform are strictly positive and \\(V \in H^2_{loc} \\), the minimizer of \\(\mathcal{E} \\) has \\(L^2\\) density.
