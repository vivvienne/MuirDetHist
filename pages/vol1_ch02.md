---
layout: page
title: vol.1 ch.02
---

## CHAPTER II. DETERMINANTS IN GENERAL, FROM THE YEAR 1693 <span style='font-variant: small-caps'>to</span> 1779.

<span style='font-variant: small-caps'>The</span> writers here to be dealt with are seven in number, viz., Leibnitz, Fontaine, Cramer, Bézout, Vandermonde, Laplace, Lagrange. Of these the first two exercised no influence on the development of the theory; the real moving spirit was
Cramer; Lagrange alone of the others may have been unaffected by this particular part of Cramer’s work.

### LEIBNITZ (1693).

[Leibnizens mathematische Schriften, herausg. v. C. I. Gerhardt. 1 Abth. ii. pp. 229, 238-240, 245. Berlin, 1850.]

In the fourth letter of the published correspondence between Leibnitz and De L’Hospital, the former incidentally mentions that in his algebraical investigations he occasionally uses numbers instead of letters, treating the numbers however as if they were letters. De L’Hospital, in his reply, refers to this, stating that he has some difficulty in believing that numbers can be as convenient or give as general results as letters. Thereupon Leibnitz, in his next letter (28th April 1693), proceeds with an explanation:—

> "Puisque vous dites que vous avés de la peine à croire qu’il soit aussi general et aussi commode de se servir des nombres que des lettres, il faut que je ne me sois pas bien expliqué. On ne sçauroit douter de la generalité en considerant qu’il est permis de se servir de 2, 3, etc., comme d’*a* ou de *b*, pour veu qu’on considere que ce ne sont pas de nombres veritables. Ainsi 2.3 ne signifie point 6 mais autant qu’*ab*. Pour ce qui est de la commodité, il y en a des tres grandes, ce qui fait que je m’en sers souvent, sur tout dans les calculs longs et difficiles ou il est aisé de se tromper. Car outre la commodité de l’épreuve par des nombres, et même par l’abjection du novenaire, j’y trouve un tres grand avantage même pour l’avancement de l’Analyse. Comme c’est une ouverture assez extraordinaire, je n’en ay pas encor parlé à d’autres, mais voicy ce que c’est. Lorsqu’on a besoin de beaucoup de lettres, n’est il pas vray que ces lettres n’expriment point les rapports qu’il y a entre les grandeurs qu’elles signifient, au lieu qu’en me servant des nombres je puis exprimer ce rapport. Par
exemple soyent proposées trois equations simples pour deux inconnues à dessein d’oster ces deux inconnues, et cela par un canon general. Je suppose
>
> $$
> \begin{align*}
> && 10 + 11x + 12y &= 0 \tag{1} \\
> & \text{et } & 20 + 21x + 22y &= 0 \tag{2} \\
> & \text{et } & 30 + 31x + 32y &= 0 \tag{3}
> \end{align*}
> $$
>
> on le nombre feint estant de deux characteres, le premier me marque de quelle equation il est, le second me marque à quelle lettre il appartient. Ainsi en calculant on trouve par tout des harmonies qui non seulement nous servent de garans, mais encor nous font entrevoir d’abord des regles ou theoremes. Par exemple ostant premierement *y* par la premiere et la seconde equation, nous aurons:
>
> $$
> \begin{array}{c} + 10 . 22 + 11 . 22x \\ - 12 . 20 - 12 . 21..\end{array} = 0 \tag{4}
> $$[^v1ch01-leibniz1693-1] et par la premiere et troisieme nous aurons:
>
> $$
> \begin{array}{c} + 10 . 32 + 11 . 32x \\ - 12 . 30 - 12 . 31..\end{array} = 0 \tag{5}
> $$
>
> on il est aise de connoistre que ces deux equations ne different qu’en ce que le charactere antecedent 2 est changé au charactere, antecedent 3. Du reste, dans un même terme d’une même equation les characteres antecedens sont les mêmes, et les characteres posterieurs font une même somme. Il reste maintenant d’oster la lettre *x* par la quatrieme et cinquieme equation, et pour cet effect nous aurons[^v1ch01-leibniz1693-2]
> 
> $$
> \begin{array}{c}
> 1_0 . 2_1 . 3_2 \\
> 1_1 . 2_2 . 3_0 \\
> 1_2 . 2_0 . 3_1
> \end{array} =
> \begin{array}{c}
> 1_0 . 2_2 . 3_1 \\
> 1_1 . 2_0 . 3_2 \\
> 1_2 . 2_1 . 3_0
> \end{array}
> $$
> 
> qui est la derniere equation delivrée des deux inconnues qu’on vouloit oster, et qui porte sa preuve avec soy par les harmonies qui se remarquent par tout, et qu’on auroit bien de la peine à decouvrir en employant des lettres *a*, *b*, *c*, sur tout lors que le nombre des lettres et des equations est grand. Une partie du secret de l'analyse consiste dans la caracteristique, c’est à dire dans l’art de bien employer les notes dont on se sert, et vous voyés, Monsieur, par ce petit echantillon que Viete et des Cartes n'en ont pas encor connu tous les mysteres. En poursuivant tant soit pen ce calcul on viendra à un *theoreme general* pour quelque nombre de lettres et d’equations simples qu’on puisse prendre. Le voicy comme je l’ay trouvé autres fois:
>
> *"Datis aequationibus quotcunque sufficientibus ad tollendas quantitates, quae simplicem gradum non egrediuntur, pro aequatione prodeunte, primo sumendae sunt omnes combinationes possibiles, quas ingreditur una tantum coefficiens uniuscujusque aequationis: secundo, eae combinationes opposita habent signa, si in eodem aequationis prodeuntis latere ponantur, quae habent tot coefficientes communes, quot sunt unitates in numero quantitatum tollendarum unitate minuto: caeterae habent eadem signa.*
> 
> "J’avoue que dans ce cas des degrés simples on auroit peut estre decouvert le même theoreme en ne se servant que de lettres à l’ordinaire, mais non pas si aisement, et ces adresses sont encor bien plus necessaires, pour decouvrir des theoremes qni servent à oster les inconnues montées à des degrés plus hauts. Par exemple, ...."

[^v1ch01-leibniz1693-1]: This is written shortly for $$\left.\begin{align*} + 10 . 22 + 11 . 22x &= 0 \\ - 12 . 20 - 12 . 21x &= 0\end{align*} \right\}$$.

[^v1ch01-leibniz1693-2]: The author here slightly changes his notation. What is meant to be indicated is

	$$10.21.32 + 11.22.30 + 12.20.31 = 10.22.31 + 11.20.32 + 12.21.30.$$

It will be seen that what this amounts to is the *formation of a rule for writing out the resultant of a set of linear equations.* When the problem is presented of eliminating *x* and *y* from the equations

$$
\begin{array}{ccc}
a + bx + cy = 0, & d + ex + fy = 0, & g + hx + ky = 0,
\end{array}
$$

Leibnitz in effect says that first of all he prefers to write 10 for *a*, 11 for *b*, and so on; that, having done this, he can all the more readily take the next step, viz., forming every possible product whose factors are one coefficient from each equation,[^v1ch01-leibniz1693-3] the result being

[^v1ch01-leibniz1693-3]: Of course, this is not exactly what Leibnitz meant to say.

$$
\begin{array}{ccl}
10.21.32, & 10.22.31, & 11.20.32, \\
11.22.30, & 12.20.31, & 12.21.30\text{ ;}
\end{array}
$$

and that, then, *one* being the number which is less by one than the number of unknowns, he makes those terms different in sign which have only *one* factor in common.

The contributions, therefore, which Leibnitz here makes to
algebra may be looked upon as three in number:—

1. A *new notation*, numerical in character and appearance, for individual members of an arranged group of magnitudes; the two members which constitute the notation being like the Cartesian co-ordinates of a point in that they denote any one of the said magnitudes by indicating its position in the group. (<span style='font-variant: small-caps'>i</span>.)
2. A rule for *forming the terms* of the expression which
equated to zero is the result of eliminating the unknowns from a set of simple equations. (<span style='font-variant: small-caps'>ii</span>.)
3. A rule for *determining the signs* of the terms in the said result. (<span style='font-variant: small-caps'>iii<span>.)