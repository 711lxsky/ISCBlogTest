## 用以测试上传图片

正常文本

![图片](img_blog1/xdu-timetower.jpg)

公式符号

$$\neq$$

$$
\begin{aligned}
    (f,K^{'}_{x}y+K^{''}_{x}y)_{F}
    &=(f^{'}+f^{''},K^{'}_{x}y+K^{''}_{x}y)_{F}\\
    &=(f^{'},K^{'}_{x}y)_{F}+(f^{''},K^{''}_{x}y)_{F}+(f^{'},K^{''}_{x}y)_{F}+(f^{''},K^{'}_{x}y)_{F}\\
    &=(f^{'},K^{'}_{x}y)_{F}+(f^{''},K^{''}_{x}y)_{F}\\
    &=(f^{'}(x),y)_{Y}+(f^{''}(x),y)_{Y}\\
    &=(f^{'}(x)+f^{''}(x),y)_{Y}\\
    &=(f(x),y)_{Y}\\
    &=(f,K_{x}y)_{F}
\end{aligned}
$$

$$
\begin{bmatrix}
    1 & x_{0} &...      & x_{0}^{n} \\
    1 & x_{1} &...  	 & x_{1}^{n} \\
    &       & \cdots  & \\
    1 & x_{n} & \dots   & x_{n}^{n}
\end{bmatrix}
\begin{bmatrix}
    a_{0}\\ a_{1}\\ ...\\ a_{n}
\end{bmatrix}=
\begin{bmatrix}
    y_{0}\\ y_{1}\\ ...\\ y_{n}
\end{bmatrix}
$$

$$
\left[   
\begin{array}{ccc|c}
    \psi(x) & g(x)   & \cdots  & a_{1n} \\
    \hline
    a_{21}  & a_{22} & \dots   & a_{2n} \\
    \vdots  & \vdots & \ddots  & \vdots \\
    a_{n1}  & a_{n2} & ...     & a_{nn}
\end{array}
\right]
$$


```java
String str = new string();
```