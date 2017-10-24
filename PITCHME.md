#HSLIDE?image=assets/banner_blue_striped.png
### EL2620 Nonlinear Control

#### Lecture 1

[Jonas Mårtensson](mailto:jonas1@kth.se)

#HSLIDE

### Today's goal

- Define a nonlinear dynamic system
- Describe distinctive phenomena in nonlinear dynamic systems
- Transform differential equations to first-order form
- Derive equilibrium points
- Qualitative behavior of linear systems

#### Covered material 
Khalil: pp 1 - 33

#HSLIDE

## What is a nonlinear system?

#VSLIDE

## A nonlinear system is a system that is not linear!

#HSLIDE

## What is a linear system?

#VSLIDE

### Linear Systems

**Definition:** Let $M$ be a signal
space. The system $S:M\rightarrow M$ is linear if for all $u,v\in M$ and $\alpha\in \mathbf{R}$

*Scaling:*
$$ S(\alpha u) = \alpha S(u) $$

*Superposition:*
$$
S(u+v)=S(u)+S(v)
$$

- What must hold for $S(0)$? |

#VSLIDE

### LTI Systems

\\begin{align}
&\sin\theta\\\\
&\cos\theta
\\end{align}

#HSLIDE

```matlab
plot(u)
plot(y)
for k=1:10
  x(k) = k^2;
end
```
Use for exmaple `help plot` to learn more avbout a function
