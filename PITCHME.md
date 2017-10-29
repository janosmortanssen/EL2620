#HSLIDE?image=assets/banner_blue_striped.png
### EL2620 Nonlinear Control

#### Lecture 1

[Jonas Mårtensson](mailto:jonas1@kth.se)

#HSLIDE
### Disposition
- 7.5 hp period 2
- 14 2-hour lectures
- 14 2-hour exercise sessions
- 3 homework assignments (2 hp each)
- 5-hour exam (1.5 hp)

#HSLIDE
### Instructors
- Jonas Mårtensson, course responsible, lectures, jonas1@kth.se
- Pedro Pereira, exercises, ppereira@kth.se
- Joana Fonseca, homework, jfgf@kth.se
- Arda Aytekin, extra (simulation), aytekin@kth.se

#HSLIDE
### Course goal
The participants should get a solid theoretical foundation of nonlinear control systems combined with good engineering understanding. 

You should after the course be able to 
- understand common nonlinear control phenomena 
- apply the most powerful nonlinear analysis methods
- use some practical nonlinear control design methods

#HSLIDE

### Examination
Homeworks are compulsory and have to be handed in on time (we are strict on this!).
- Homework 1, Nov 17
- Homework 2, Nov 30
- Homework 3, Dec 14 

Written 5h exam 08-13 on January 11, 2018
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
