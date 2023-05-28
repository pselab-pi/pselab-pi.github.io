---
title: SOCP
linktitle: Second-order cone programming (SOCP)
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  optimization:
    parent: optimization
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

Here are some more tips for getting started with academia:

## Basic formulation

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

Nullam vel molestie justo. $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$ Curabitur vitae efficitur leo. In hac habitasse platea dictumst. Sed pulvinar mauris dui, eget varius purus congue ac. Nulla euismod, lorem vel elementum dapibus, nunc justo porta mi, sed tempus est est vel tellus. Nam et enim eleifend, laoreet sem sit amet, elementum sem. Morbi ut leo congue, maximus velit ut, finibus arcu. In et libero cursus, rutrum risus non, molestie leo. Nullam congue quam et volutpat malesuada. Sed risus tortor, pulvinar et dictum nec, sodales non mi. Phasellus lacinia commodo laoreet. Nam mollis, erat in feugiat consectetur, purus eros egestas tellus, in auctor urna odio at nibh. Mauris imperdiet nisi ac magna convallis, at rhoncus ligula cursus.

$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$

$$
\begin{align}
a_1 &= \beta_0 \\\\\\
b_1 &= \beta_1 \\\\\\
c_1 &= \beta_2 \\\\\\
d_1 &= \beta_3
\end{align}
$$

$$
\begin{align}
	&E=mc^2 \label{c:eq1}
\end{align}
$$
In equation $\eqref{c:eq1}$, see if this tag works fine.


```bash
## some code
for i = 1:3
```

```bash
mkdir -p output/src; for i in ....
mkdir new_web
cd .
source ~/.bash_profile
echo "Welcome, Jane Doe" 
```

```python
for i = 1:3:
    println(i)
```

```julia
## julia code
for i = 1:3
    println(i)
end
```

```matlab
%% matlab code
x = linspace(-2*pi,2*pi);
y1 = sin(x);
y2 = cos(x);

figure
plot(x,y1,x,y2)
```

```javascript I'm A tab
console.log('Code Tab A');
```

```javascript I'm tab B
console.log('Code Tab B');
```

$$
\begin{align}
  & S_i = S_{G_i} - S_{D_i} = \sum_{k=1}^{n} S_{ik},\quad \forall i \in {\cal I}, \\\\\\
  & I_i = I_{G_i} - I_{D_i} = \sum_{k=1}^{n} I_{ik} \\\\\\
  & \mathbf{I} = \mathbf{Y}_{bus} \mathbf{V} \\\\\\
\end{align}
$$

In equation \eqref{eq:sample}, we find the value of an
interesting integral:

$$
\begin{align}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:sample}\\\\\\
\end{align}
$$

$$
\begin{align}
  & I_i = \sum_{k=1}^{n} Y_{ik} V_k
\end{align}
$$

Power Flow equations:

$$
\begin{align} % Bergen p325
    & S\_i = S\_{G\_i} - S\_{D\_i} = \sum\_{k=1}^{n} S\_{ik}\\\\\\
    & I\_i = I\_{G\_i} - I\_{D\_i} = \sum\_{k=1}^{n} I\_{ik}\\\\\\
    & \mathbf{I} = \mathbf{Y}\_{bus} \mathbf{V}\\\\\\
    & I\_i = \sum\_{k=1}^{n} Y\_{ik} V\_k\\\\\\
    & S\_i = V\_i I\_i^\*\\\\\\
    & \hspace{4mm}
        = V\_i 
            \Big(  
                \sum\_{k=1}^{n} Y\_{ik} V\_k
            \Big)^\*
    %             \\\\\\
    % & \hspace{4mm}
        = V\_i 
            \sum\_{k=1}^{n} 
                Y^\*\_{ik} V^\*\_k 
                \\\\\\
    & \hspace{4mm}
        = \vert V\_i \vert e^{j\theta\_{i}}
            \sum\_{k=1}^{n} 
                (G\_{ik} - j B\_{ik}) 
                \vert V\_k \vert e^{-j\theta\_{k}}
                \\\\\\
    & \hspace{4mm}
        = \sum\_{k=1}^{n} 
            \vert V\_i \vert 
            \vert V\_k \vert
                (\cos{\theta\_{ik}} + j \sin{\theta\_{ik}})
                    (G\_{ik} - j B\_{ik}) 
                    \\\\\\
    & P\_i
        % = P\_{G\_i} - P\_{D\_i}
        = \sum\_{k=1}^{n} 
            \vert V\_i \vert 
            \vert V\_k \vert
                (G\_{ik}\cos{\theta\_{ik}} + B\_{ik} \sin{\theta\_{ik}})
                    \\\\\\
    & Q\_i
        % = Q\_{G\_i} - Q\_{D\_i}
        = \sum\_{k=1}^{n} 
            \vert V\_i \vert 
            \vert V\_k \vert
                (G\_{ik}\sin{\theta\_{ik}} - B\_{ik} \cos{\theta\_{ik}})
                    % \\\\\\
\end{align}
$$

Cras aliquam rhoncus ipsum, in hendrerit nunc mattis vitae. Duis vitae efficitur metus, ac tempus leo. Cras nec fringilla lacus. Quisque sit amet risus at ipsum pharetra commodo. Sed aliquam mauris at consequat eleifend. Praesent porta, augue sed viverra bibendum, neque ante euismod ante, in vehicula justo lorem ac eros. Suspendisse augue libero, venenatis eget tincidunt ut, malesuada at lorem. Donec vitae bibendum arcu. Aenean maximus nulla non pretium iaculis. Quisque imperdiet, nulla in pulvinar aliquet, velit quam ultrices quam, sit amet fringilla leo sem vel nunc. Mauris in lacinia lacus.

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum. Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at.


## Dual of LP

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

Nullam vel molestie justo. Curabitur vitae efficitur leo. In hac habitasse platea dictumst. Sed pulvinar mauris dui, eget varius purus congue ac. Nulla euismod, lorem vel elementum dapibus, nunc justo porta mi, sed tempus est est vel tellus. Nam et enim eleifend, laoreet sem sit amet, elementum sem. Morbi ut leo congue, maximus velit ut, finibus arcu. In et libero cursus, rutrum risus non, molestie leo. Nullam congue quam et volutpat malesuada. Sed risus tortor, pulvinar et dictum nec, sodales non mi. Phasellus lacinia commodo laoreet. Nam mollis, erat in feugiat consectetur, purus eros egestas tellus, in auctor urna odio at nibh. Mauris imperdiet nisi ac magna convallis, at rhoncus ligula cursus.

Cras aliquam rhoncus ipsum, in hendrerit nunc mattis vitae. Duis vitae efficitur metus, ac tempus leo. Cras nec fringilla lacus. Quisque sit amet risus at ipsum pharetra commodo. Sed aliquam mauris at consequat eleifend. Praesent porta, augue sed viverra bibendum, neque ante euismod ante, in vehicula justo lorem ac eros. Suspendisse augue libero, venenatis eget tincidunt ut, malesuada at lorem. Donec vitae bibendum arcu. Aenean maximus nulla non pretium iaculis. Quisque imperdiet, nulla in pulvinar aliquet, velit quam ultrices quam, sit amet fringilla leo sem vel nunc. Mauris in lacinia lacus.

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum. Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at.
