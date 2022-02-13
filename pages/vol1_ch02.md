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

<div class="tabs">
<input type="radio" id="tab1" name="tab-control" checked>
<input type="radio" id="tab2" name="tab-control">
<ul>
<li title="Original text in Muir's"><label for="tab1" role="button">Original<!--tab header--></label></li>
<li title="English translation"><label for="tab2" role="button">English<!--tab header--></label></li>
</ul>
<div class="slider">
<div class="indicator"></div>
</div>
<div class="content">
<section markdown="1">

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
> $$
>
> [^v1ch01-leibniz1693-1] et par la premiere et troisieme nous aurons:
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
> "J’avoue que dans ce cas des degrés simples on auroit peut estre decouvert le même theoreme en ne se servant que de lettres à l’ordinaire, mais non pas si aisement, et ces adresses sont encor bien plus necessaires, pour decouvrir des theoremes qui servent à oster les inconnues montées à des degrés plus hauts. Par exemple, ...."

</section>
<section markdown="1">

English translation (of all except the last paragraph) by Thomas Freeman Cope, from Smith, D. E., & Cope, T. F. (1929). Leibniz on Determinants. In *A source book in Mathematics* (pp. 267–269). essay, McGraw-Hill book company, inc. ([online copy](https://archive.org/details/sourcebookinmath00smit/page/267/mode/2up) @ The Internet Archive). English translation of last paragraph is via Google Translate, added by MuirDetHist.

> Since you say that you have difficulty in believing that it is as general and as convenient to use numbers instead of letters, I must not have explained myself very well. There can be no doubt about the generality if one considers that it is permissible to use 2, 3, etc., like *a* or *b*, provided that it is understood that these are not really numbers. Thus 2 . 3 does *not* denote 6 but rather *ab*. As regards convenience, it is so considerable that I myself often use them[^Thomas-Freeman-Cope-note-1] especially in long and difficult computations where it is easy to make mistakes. For besides the convenience of checking by numbers and even by the casting out of nines, I find their use a very great advantage even in the analysis itself. As this is quite an extraordinary discovery, I have not yet spoken to any others about it, but here is what it is. When one has need of many letters, is it not true that these letters do not at all express the relationship among the magnitudes they represent, while by the use of numbers I am able to express this relationship. For example, consider three simple equations in two unknowns, the object being to eliminate the two unknowns and indeed by a general law. I suppose that
>
> $$
> \begin{align*}
> && 10 + 11x + 12y &= 0 \tag{1} \\
> & \text{and } & 20 + 21x + 22y &= 0 \tag{2} \\
> & \text{and } & 30 + 31x + 32y &= 0 \tag{3}
> \end{align*}
> $$
>
> where, in the pseudo number of two digits, the first tells me the equation in which it is found, the second, the letter to which it belongs. Thus on carrying out the computation, we find throughout a harmony which not only serves as a check but even makes us
suspect at first glance some rules or theorems. For example, eliminating *y* first from the first and second equations, we shall have:
>
> $$
> \begin{array}{c} + 10 . 22 + 11 . 22x \\ - 12 . 20 - 12 . 21..\end{array} = 0 \tag{4}
> $$
>
> [^Thomas-Freeman-Cope-note-2] and from the first and third:
>
> $$
> \begin{array}{c} + 10 . 32 + 11 . 32x \\ - 12 . 30 - 12 . 31..\end{array} = 0 \tag{5}
> $$
> 
> where it is easy to recognize that these two equations differ only in that the anterior character 2 is changed to the anterior character 3. Moreover, in similar terms of an equation, the anterior characters are the same and the posterior characters have the same sum. It remains now to eliminate the letter *x* from the fourth and fifth equations, and, as the result, we shall have:[^Thomas-Freeman-Cope-note-3]
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
> which is the final equation freed from the two unknowns that we wished to eliminate, which carries its own proof along with itself from the harmony observable throughout, and which we should find very troublesome to discover using the letters *a*, *b*, *c*, especially when the number of letters and equations is large. A part of the secret of analysis is the characteristic, rather the art, of using notation well, and you see, Sir, by this little example, that Vieta and Descartes did not even know all of its mysteries. Continuing the calculation in this fashion, one will come to a general theorem for any desired numbers of letters and simple equations. Here is
what I have found it to be on other occasions:—
>
> *Given any number of equations which is sufficient for eliminating the unknown quantities which do not exceed the first degree:—for the final equation are to be taken, first, all possible combinations of coefficients, in which one coefficient only from each equation is to enter; secondly, those combinations, after they are placed on the same side of the final equation, have different signs if they have as many factors alike as is indicated by the number which is less by one than the number of unknown quantities: the rest have the same sign.*
>

The following paragraph is obtained via Google Translate.

> I admit that in this case of simple degrees one would perhaps have discovered the same theorem by using only ordinary letters, but not so easily, and these addresses are still much more necessary, to discover theorems which are used to remove the unknowns mounted to higher degrees. For example, ....

</section>
</div>
</div>

[^v1ch01-leibniz1693-1]: This is written shortly for $$\left.\begin{align*} + 10 . 22 + 11 . 22x &= 0 \\ - 12 . 20 - 12 . 21x &= 0\end{align*} \right\}$$.

[^v1ch01-leibniz1693-2]: The author here slightly changes his notation. What is meant to be indicated is

	$$10.21.32 + 11.22.30 + 12.20.31 = 10.22.31 + 11.20.32 + 12.21.30.$$

[^Thomas-Freeman-Cope-note-1]: (English translator's note) [*I.e.* numbers in place of letters.]

[^Thomas-Freeman-Cope-note-2]: (English translator's note) [This is an abbreviated form, as Muir points out, for $$\left.\left.\begin{align*} + 10 . 22 + 11 . 22x &= 0 \\ - 12 . 20 - 12 . 21x &= 0\end{align*} \right\}\right]$$.

[^Thomas-Freeman-Cope-note-3]: (English translator's note) [The notation here has been slightly changed. What is clearly meant is, as Muir notes,

	$$10.21.32 + 11.22.30 + 12.20.31 = 10.22.31 + 11.20.32 + 12.21.30.]$$

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