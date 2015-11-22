[Exploratoria]( http://exploratoria.github.io ) &raquo; [Exhibits]( http://exploratoria.github.io/exhibits/ ) &raquo;
[Mathematics & Patterns]( http://exploratoria.github.io/exhibits/mathematics/ ) &raquo;

<center>
# Lorenz Attractor
</center>

<span style=display:none>_View as a web page to see the content of this iframe_</span>
<iframe src=http://exploratoria.github.io/lib/code-edit-view/code-edit-view.html#http://exploratoria.github.io/exhibits/mathematics/lorenz-attractor/lorenz-attractor.html width=100% height=500px></iframe>

<span style=display:none; >[You are now in GitHub source code view - Click here to view as a web page] (http://exploratoria.github.io/exhibits/mathematics/lorenz-attractor/index.html 'View file as a web page') </span>
<input type=button value='You are now in GitHub web page view - Click here to view as source code' onclick=window.location.href='https://github.com/exploratoria/exploratoria.github.io/tree/master/exhibits/mathematics/lorenz-attractor/'; />

[Lorenz Attractor - Full Screen](http://exploratoria.github.io/exhibits/mathematics/lorenz-attractor/lorenz-attractor.html)

The <a href=https://en.wikipedia.org/wiki/Lorenz_system>Lorenz attractor</a>

### Things to Try

* Click the "Update View" button to see several instances of the attractor. The curve starts at a random point each time but the resulting figure looks the same. This is what is meant by an attractor.

* Increase the variable named "multiplier" to see the curve develop faster

* Change the values of the parameters named "beta" (&beta;), "rho" (&rho;) and "sigma" (&sigma;) to alter the nature of the attractor. You may also need to change the value of "scale" in order to see the developing curve, or zoom the view out.
 
### About the Code


### A Little Math

The Lorenz attractor is the solution of the coupled differential equations

\\[ \begin{align}
\frac{ dx }{ dt } &= \sigma ( y - x ) \\\\
\frac{ dy }{ dt } &= x ( \rho - z ) - y \\\\
\frac{ dz }{ dt } &= x y - \beta z
\end{align} \\]

The fractions are derivatives that describe the rate of change of coordinates along the curve. If you don't know what that means then not to worry! Use this trick: move the denominators of the fractions to the other sides of the equations

\\[ \begin{align}
dx &= \sigma ( y - x ) dt \\\\
dy &= ( x ( \rho - z ) - y ) dt\\\\
dz &= ( x y - \beta z ) dt
\end{align} \\]

and think of the "d" as meaning difference or change in the coordinates. This is how the solution to the equation is found in the code.