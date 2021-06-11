
:microphone: ESA 2021

# Early Career Fellows Symposium: _The right kind of machine learning for a changing planet?_

# Contributed Talk: _Are we learning to build better models at the cost of better decisions?_

# Ignite Talk: _Cyberinfrastructure for Ecological Forecasting_ 

----

# Symposium

## _The right kind of machine learning for a changing planet?_

## Background / Question / Methods

Advances in both available data and computing power have begun to open the door to a greater role for machine learning (ML) in addressing some of our planet's most pressing environmental problems, such as the growing frequency and intensity of wildfire, over-exploited fisheries, declining biodiversity, and zoonotic pandemics. But will such approaches really help us tackle a changing planet? The reliance of dominant machine learning approaches on existing data can make them a valuable tool for automating well-understood steps in an analysis, but may also make them a poor tool to predict the long-term dynamics of a no-analogue future and the non-representative distribution of available ecological data. Supervised Learning methods have proven very successful in tasks such as image classification, with the promise of being able to automate species identification from cameras, acoustic sensors or satellite images. Unsupervised learning methods hold out a more ambitious promise of identifying features or making predictions without first requiring a large training set labeled data. The short-term effectiveness of such approaches may not prove a good guide to their long-term performance, though approaches such as iterative forecasting can provide an important check on the habit of such methods to over-fit available data. But the least attention has been paid to what may be the most promising member of the ML triumvirate: Reinforcement Learning (RL). RL tains a software agent to maximize some objective -- notable examples include navigation in autonomous robots or Google's AlphaZero agent that recently defeated the world's best players of Go, Chess, and Shogi. Unlike supervised or unsupervised learning, RL requires agents to make decisions in dynamic and uncertain environments that plan ahead and change the state of the board. Also unlike other approaches, such agents are typically trained, not on mountains of data alone, but on simulations.


## Results / Conclusions

I describe how this creates a bridge between the rich, mechanistic or process based models of our field and the power of ML to discover creative solutions to complex decision problems. Rather than seeking to displace process-based models of the past century with opaque machines, I illustrate how we can use those models to drive realistic simulations which we can then train leading RL algorithms to manage. I illustrate this approach with examples from fisheries management, ecosystem tipping points, and wildfire spread. These examples are only a proof-of-principle which illuminate not only the promise, but also some of the pitfalls ahead. The pitfalls are not only technical, but include issues of ethics and power, particularly if the algorithms or data are proprietary. I conclude with a discussion of how an open, transparent and reproducible approach can help mitigate some concerns, while also offering a more effective interface between teams of researchers from both ecological and computer sciences.




# Contributed Talk

## _Are we learning to build better models at the cost of better decisions?_

- Session Title: Conservation Planning, Policy, And Theory 2
- Scheduled For: Monday, August 2, 2021: 2:30 PM - 3:30 PM 

Abstract: 
Background/Question/Methods

Uncertainty has always been a central issue confronting ecological management and decision making.  While some uncertainty is irreducible due to the inherent variation of environment and demographics, much uncertainty arises from our limited knowledge of those processes, reflected in the choice of possible functions and parameters we use to model them.  Consequently, a rich suite of techniques for addressing and reducing model uncertainty have been developed, often emphasizing the importance of an iterative or adaptive approach in which the choices of models and parameters are refined in light of new observations and management outcomes.  Unfortunately, even the best of such adaptive approaches can push in the direction of worse decisions.

I consider two such techniques: (1) an iterative forecasting approach, a powerful technique which avoids the selection of models that over-fit the data that is becoming increasingly possible in real world applications thanks to the rapid growth of available ecological data, and (2) an adaptive management approach, which explicitly integrates over uncertainty to maximize expected real-world value rather than more abstract notion of forecast skill. I apply these to a very simple and familiar conservation decision problem: selecting a sustainable harvest policy, given uncertainty over two possible models.

## Results/Conclusions 

In my example problem, I find that both iterative forecasting and adaptive management cycles lead to a rapid deterioration in management outcomes they are intending to optimize. Management under either approach leads to overfishing, depressed biomass, and depressed economic yields relative to a strategy that does not attempt to learn or reduce model uncertainty, or even one which merely assumes one of the two models is correct.   The intuition for this result can be demonstrated on a napkin, which makes it clear that this is not a problem of model fitting and that no model choice technique would choose the model which gives the best outcomes.  This result highlights a pitfall in how any available or emerging approaches which no amount of data can solve, but some napkin-sized theory can help.

# Ecological Forecasting Cyberinfrastructure

