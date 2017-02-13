
***Everyone has these pieces code that are as embarrassing to her/him as she/he is proud of. Here is one of mine.***

# SCSIM
**Task**

The University of Applied Sciences Karlsruhe created a <a href="http://www.iwi.hs-karlsruhe.de/scs/download/Handbuch_EN.pdf">Supply Chain Simulator</a> and made it accesible for other universities. During my bachelors we had to take place in a competition based on this simulator.

The goal was to maximize profit of a bycicle manufacturing company by optimizing production.

The model factory contained 14 different workplaces. The bycicles were produced for children, women and men. These 3 end products were each composed of 27 in-house products and 29 purchased items.

**Strategy**

The obvious strategy was to use simple heuristics we learned before to tweak input parameters. Other teams have shown that these heuristics are definitely capable to deliver sufficient results. Anyway, I could not stop thinking how to solve this problem the best possible way.

And so I roughly rebuild the Simulator itself ;)

**Result**

The pictures below show the actual simulations (or reality from game perspective) and my according simulations for two different days, which were pretty accurate. Different in-house products (colors) are manufactured in different workplaces (y) in a specific period of time (x).
<p align="center">
  first and third: actual simulations; second and fourth: my according simulations
  <br>
  <img src="https://raw.githubusercontent.com/Lausbert/SCSIM/master/Examples/reality1.png" width="200" height="200">
  <img src="https://raw.githubusercontent.com/Lausbert/SCSIM/master/Examples/simulation1.png" width="200" height="200">
  <img src="https://raw.githubusercontent.com/Lausbert/SCSIM/master/Examples/reality2.png" width="200" height="200">
  <img src="https://raw.githubusercontent.com/Lausbert/SCSIM/master/Examples/simulation2.png" width="200" height="200">
</p>

**Final Thought**

The effort needed to rebuild the simulator by no means justified the game-related benefit and I could have saved me one or two sleeples nights. BUT (!) it was fun though :)

