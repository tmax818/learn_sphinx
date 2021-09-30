Math
=====

When the math is only one line of text, it can also be given as a directive argument:

.. math:: (a + b)^2 = a^2 + 2ab + b^2

There is also an option nowrap that prevents any wrapping of the given math in a math environment. When you give this option, you must make sure yourself that the math is properly set up. For example:

.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}