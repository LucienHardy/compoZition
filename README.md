# compoZition
LaTeX style file using TikZ to draw diagrams for operational Quantum Theory.  This is available in compozition.sty
The Z in compoZition is homage to TikZ.   
Here is some simple example code
\begin{compose}
\crectangle{A}{2.5}{2.3}{0,0} \csymbol{B}
\thispoint{d}{0,-4.5} \thispoint{u}{0,4.5}
\jointbnoarrow[right]{d}{0}{A}{0} \csymbol{a}
\jointbnoarrow[right]{A}{0}{u}{0} \csymbol{b}
\end{compose}
This draws a rectangle centered at (0,0) of width 2.5 and height 2.3 with a B inside it.  Then it has "wires" sticking out of it from above and below to points above and below.  
I will add an example file with multiple examples taken from my book.   
