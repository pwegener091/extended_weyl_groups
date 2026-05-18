# extended_weyl_groups
Files for the paper "Extended Weyl groups, Hurwitz transitivity and weighted projective lines I: Generalities and the tubular case" by B. Baumeiser, P. Wegener and S. Yahiatene

The jupyter notebook "Example_Cox_Element" contains Sage-Code to verfify the assertions of Example 5.22.

We fix the Basis $B = \{\alpha_1, \ldots, \alpha_6, a, b\}$ of the root system of type $E_6^{(1,1)}$.

For the reflections $s_{\beta_1}, s_{\beta_2}, \ldots, s_{\beta_8}$ as well as
for the reflections $s_{\alpha_0}, s_{\alpha_1}, \ldots, s_{\alpha_6}, s_{\alpha_4^*}$
we compute the transformation matrices with respect to the Basis $B$ (which we call by abuse of notation also $s_{\alpha_i}, s_beta_i}$ etc.).

We denote by $c1$ the trasformation matrix corresponding to the product $s_{\beta_1} s_{\beta_2} \cdots s_{\beta_8}$.

We denote by $c2$ the trasformation matrix corresponding to the product $s_{\alpha_1} s_{\alpha_2} s_{\alpha_3} s_{\alpha_5} s_{\beta_6} s_{\alpha_0} s_{\alpha_4} s_{\alpha_4^*}$.

We verify that $c1 = c2$.
