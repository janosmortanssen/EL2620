#HSLIDE?image=assets/banner_blue_striped.png
### Title

[Jonas Mårtensson](mailto:jonas1@kth.se)

**Department of Automatic Control**,

**KTH Royal Institute of Technology**

#HSLIDE

# Title
## Title
### Title
#### Agenda

- Topic 1
- Topic 2

<img src="assets/banner_blue_striped.png" style="width: 400px;" align="right" />

#HSLIDE

## Linear Systems

Definition: Let $M$ be a signal
space. The system $S:M\rightarrow M$ is linear if for all $u,v\in M$ and $\alpha\in \mathbf{R}$
\begin{align*}
S(\alpha u) &= \alpha S(u)\qquad\qquad\qquad \text{\textcolor{red}{scaling}}\\
S(u+v)&=S(u)+S(v)\qquad \text{\textcolor{red}{superposition}}
\end{align*}

\textbf{Example:} Linear time-invariant systems
\begin{align*}
\dot x(t) &= Ax(t)+Bu(t),\quad  y(t)=Cx(t), \quad x(0)=0\\
y(t) &= g(t) \ast u(t)=\int_{0}^tg(\tau)u(t-\tau)d\tau\\
Y(s) &= G(s)U(s)
\end{align*}

Notice the importance to have zero initial conditions
