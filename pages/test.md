---
layout: page
title: test page
permalink: /test_page
---

<div class="tabs">
<input type="radio" id="tab1" name="tab-control" checked>
<input type="radio" id="tab2" name="tab-control">
<ul>
<li title="show original text"><label for="tab1" role="button">Original<!--tab header--></label></li>
<li title="show English translation"><label for="tab2" role="button">English<!--tab header--></label></li>
</ul>
<div class="slider">
<div class="indicator"></div>
</div>
<div class="content">
<section>
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
</section>
<section>
CONTENT_2 English translation
</section>
</div>
</div>

[^v1ch01-leibniz1693-1]: This is written shortly for $$\left.\begin{align*} + 10 . 22 + 11 . 22x &= 0 \\ - 12 . 20 - 12 . 21x &= 0\end{align*} \right\}$$.

[^v1ch01-leibniz1693-2]: The author here slightly changes his notation. What is meant to be indicated is

	$$10.21.32 + 11.22.30 + 12.20.31 = 10.22.31 + 11.20.32 + 12.21.30.$$