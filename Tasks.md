# A compiled list of problems being solved by newer techniques in AI.

## Problem agnostic
 - Marvin Minsky, Steps toward Artificial Intelligence, Proceedings of the IRE, 1961. [[Paper]](http://staffweb.worc.ac.uk/DrC/Courses%202010-11/Comp%203104/Tutor%20Inputs/Session%209%20Prep/Reading%20material/Minsky60steps.pdf) (discusses issues in RL such as the "credit assignment problem")

## Vision

## Natural Language

## Pattern recognition

## Planning, optimization and control

### Reading
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (1st Edition, 1998) [[Book]](http://webdocs.cs.ualberta.ca/~sutton/book/ebook/the-book.html) [[Code]](https://webdocs.cs.ualberta.ca/~sutton/book/code/code.html)
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (2nd Edition, in progress, 2017) [[Book]](http://incompleteideas.net/sutton/book/the-book.html) [[Code]](http://incompleteideas.net/sutton/book/code/code.html)
 - Csaba Szepesvari, Algorithms for Reinforcement Learning [[Book]](http://www.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
 - David Poole and Alan Mackworth, Artificial Intelligence: Foundations of Computational Agents [[Book Chapter]](http://artint.info/html/ArtInt_262.html)
 - Dimitri P. Bertsekas and John N. Tsitsiklis, Neuro-Dynamic Programming [[Book (Amazon)]](http://www.amazon.com/Neuro-Dynamic-Programming-Optimization-Neural-Computation/dp/1886529108/ref=sr_1_3?s=books&ie=UTF8&qid=1442461075&sr=1-3&refinements=p_27%3AJohn+N.+Tsitsiklis+Dimitri+P.+Bertsekas) [[Summary]](http://www.mit.edu/~dimitrib/NDP_Encycl.pdf)
 - Mykel J. Kochenderfer, Decision Making Under Uncertainty: Theory and Application [[Book (Amazon)]](http://www.amazon.com/Decision-Making-Under-Uncertainty-Application/dp/0262029251/ref=sr_1_1?ie=UTF8&qid=1441126550&sr=8-1&keywords=kochenderfer&pebp=1441126551594&perid=1Y6RG2EGRD26659CJHH9)

### Problems
 - Dynamic Programming (DP):
   - Christopher J. C. H. Watkins, Learning from Delayed Rewards, Ph.D. Thesis, Cambridge University, 1989. [[Thesis]](https://www.cs.rhul.ac.uk/home/chrisw/new_thesis.pdf)
 - Monte Carlo:
   - Andrew Barto, Michael Duff, Monte Carlo Inversion and Reinforcement Learning, NIPS, 1994. [[Paper]](http://papers.nips.cc/paper/865-monte-carlo-matrix-inversion-and-reinforcement-learning.pdf)
   - Satinder P. Singh, Richard S. Sutton, Reinforcement Learning with Replacing Eligibility Traces, Machine Learning, 1996. [[Paper]](http://www-all.cs.umass.edu/pubs/1995_96/singh_s_ML96.pdf)
 - Temporal-Difference:
   - Richard S. Sutton, Learning to predict by the methods of temporal differences. Machine Learning 3: 9-44, 1988. [[Paper]](http://webdocs.cs.ualberta.ca/~sutton/papers/sutton-88-with-erratum.pdf)
 - Q-Learning (Off-policy TD algorithm):
   - Chris Watkins, Learning from Delayed Rewards, Cambridge, 1989. [[Thesis]](http://www.cs.rhul.ac.uk/home/chrisw/thesis.html)
 - Sarsa (On-policy TD algorithm):
   - G.A. Rummery, M. Niranjan, On-line Q-learning using connectionist systems, Technical Report, Cambridge Univ., 1994. [[Report]](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=0CDIQFjACahUKEwj2lMm5wZDIAhUHkg0KHa6kAVM&url=ftp%3A%2F%2Fmi.eng.cam.ac.uk%2Fpub%2Freports%2Fauto-pdf%2Frummery_tr166.pdf&usg=AFQjCNHz6IrgcaaO5lzC7t8oEIBY9epozg&sig2=sa-emPme1m5Jav7YmaXsNQ&cad=rja)
   - Richard S. Sutton, Generalization in Reinforcement Learning: Successful examples using sparse coding, NIPS, 1996. [[Paper]](http://webdocs.cs.ualberta.ca/~sutton/papers/sutton-96.pdf)
 - R-Learning (learning of relative values)
   - Andrew Schwartz, A Reinforcement Learning Method for Maximizing Undiscounted Rewards, ICML, 1993. [[Paper-Google Scholar]](https://scholar.google.com/scholar?q=reinforcement+learning+method+for+maximizing+undiscounted+rewards&hl=en&as_sdt=0&as_vis=1&oi=scholart&sa=X&ved=0CBsQgQMwAGoVChMIho6p_MOQyAIVwh0eCh3XWAwM)
 - Function Approximation methods (Least-Square Temporal Difference, Least-Square Policy Iteration)
   - Steven J. Bradtke, Andrew G. Barto, Linear Least-Squares Algorithms for Temporal Difference Learning, Machine Learning, 1996. [[Paper]](http://www-anw.cs.umass.edu/pubs/1995_96/bradtke_b_ML96.pdf)
   - Michail G. Lagoudakis, Ronald Parr, Model-Free Least Squares Policy Iteration, NIPS, 2001. [[Paper]](http://www.cs.duke.edu/research/AI/LSPI/nips01.pdf) [[Code]](http://www.cs.duke.edu/research/AI/LSPI/)
 - Policy Search / Policy Gradient
   - Richard Sutton, David McAllester, Satinder Singh, Yishay Mansour, Policy Gradient Methods for Reinforcement Learning with Function Approximation, NIPS, 1999. [[Paper]](http://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf)
   - Jan Peters, Sethu Vijayakumar, Stefan Schaal, Natural Actor-Critic, ECML, 2005. [[Paper]](https://homes.cs.washington.edu/~todorov/courses/amath579/reading/NaturalActorCritic.pdf)
   - Jens Kober, Jan Peters, Policy Search for Motor Primitives in Robotics, NIPS, 2009. [[Paper]](http://papers.nips.cc/paper/3545-policy-search-for-motor-primitives-in-robotics.pdf)
   - Jan Peters, Katharina Mulling, Yasemin Altun, Relative Entropy Policy Search, AAAI, 2010. [[Paper]](http://www.kyb.tue.mpg.de/fileadmin/user_upload/files/publications/attachments/AAAI-2010-Peters_6439%5b0%5d.pdf)
   - Freek Stulp, Olivier Sigaud, Path Integral Policy Improvement with Covariance Matrix Adaptation, ICML, 2012. [[Paper]](http://arxiv.org/pdf/1206.4621v1.pdf)
   - Nate Kohl, Peter Stone, Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion, ICRA, 2004. [[Paper]](http://www.cs.utexas.edu/~pstone/Papers/bib2html-links/icra04.pdf)
   - Marc Deisenroth, Carl Rasmussen, PILCO: A Model-Based and Data-Efficient Approach to Policy Search, ICML, 2011. [[Paper]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf)
   - Scott Kuindersma, Roderic Grupen, Andrew Barto, Learning Dynamic Arm Motions for Postural Recovery, Humanoids, 2011. [[Paper]](http://www-all.cs.umass.edu/pubs/2011/kuindersma_g_b_11.pdf)
   - Konstantinos Chatzilygeroudis, Roberto Rama, Rituraj Kaushik, Dorian Goepp, Vassilis Vassiliades, Jean-Baptiste Mouret, Black-Box Data-efficient Policy Search for Robotics, IROS, 2017. [[Paper](https://arxiv.org/abs/1703.07261)]
 - Hierarchical RL
   - Richard Sutton, Doina Precup, Satinder Singh, Between MDPs and Semi-MDPs: A Framework for Temporal Abstraction in Reinforcement Learning, Artificial Intelligence, 1999. [[Paper]](https://webdocs.cs.ualberta.ca/~sutton/papers/SPS-aij.pdf)
   - George Konidaris, Andrew Barto, Building Portable Options: Skill Transfer in Reinforcement Learning, IJCAI, 2007. [[Paper]](http://www-anw.cs.umass.edu/pubs/2007/konidaris_b_IJCAI07.pdf)
 - Deep Learning + Reinforcement Learning (A sample of recent works on DL+RL)
   - V. Mnih, et. al., Human-level Control through Deep Reinforcement Learning, Nature, 2015. [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D)
   - Xiaoxiao Guo, Satinder Singh, Honglak Lee, Richard Lewis, Xiaoshi Wang, Deep Learning for Real-Time Atari Game Play Using Offline Monte-Carlo Tree Search Planning, NIPS, 2014. [[Paper]](http://papers.nips.cc/paper/5421-deep-learning-for-real-time-atari-game-play-using-offline-monte-carlo-tree-search-planning.pdf)
   - Sergey Levine, Chelsea Finn, Trevor Darrel, Pieter Abbeel, End-to-End Training of Deep Visuomotor Policies. ArXiv, 16 Oct 2015. [[ArXiv]](http://arxiv.org/pdf/1504.00702v3.pdf)
   - Tom Schaul, John Quan, Ioannis Antonoglou, David Silver, Prioritized Experience Replay, ArXiv, 18 Nov 2015. [[ArXiv]](http://arxiv.org/pdf/1511.05952v2.pdf)
   - Hado van Hasselt, Arthur Guez, David Silver, Deep Reinforcement Learning with Double Q-Learning, ArXiv, 22 Sep 2015. [[ArXiv]](http://arxiv.org/abs/1509.06461)
   - Volodymyr Mnih, Adrià Puigdomènech Badia, Mehdi Mirza, Alex Graves, Timothy P. Lillicrap, Tim Harley, David Silver, Koray Kavukcuoglu, Asynchronous Methods for Deep Reinforcement Learning, ArXiv, 4 Feb 2016. [[ArXiv]](https://arxiv.org/abs/1602.01783)


## Generation