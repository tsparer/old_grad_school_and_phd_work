### old grad school and phd work
# A repo of writings and work from roughly 2012 to 2016:  Applying Bayesian Learning + Optimization to Creativity, Insight problems and Reversal learning:

Background Below

(Big question: what does an "optimally adaptive" system look-like- when the environment-to-be-adapted-to is unspecifiable and constantly changing- 
and what can processes like creativity and human/animal learning tell us about those kind of adaptive systems?

(Big constraints: Problem of Induction (Hume), Underdetermination (Quine), Computational Complexity (np hardness of change- Kwisthout, Wareheim), Turing Decidability, Wolpert (no free lunch, and his Godel-adjacent work) Frame Problem, etc.) )

# Background

## Explanandum
Phenomonologically, "Learning Processes" as diverse as Child Development (Piaget), Scientific Theory Development (Kuhn), and Creativity/Insight often exhibit a step-function, 
or stage like character:  Small local errors/unexpected data do not (necessarily) lead to correspondinng (small) incremental changes in a knowledge schema, theory, or percept; significant change, when it does occur, often happens in 
rapid / stage like mannner, leading to a qualitative reorganization of top-down assumptions.

### Claim 1
Given the phenomenolgical similarities at multiple levels of learninng processes; Perhaps these processes share an underlying mechanism.  That mechanism should lead to the observed
nonlinear learning results.

### Constraints/observation
## Any adaptive/self regulating (learning) system is constrained by at least 2 factors:  
1) The need for an accurate-enough model of the world: to act on the world effectively (and to maintain itself far-from-thermodynamic-equilbrium) an adaptive system needs (or is) a model of the system regulated.  (Conant + Ashby, Good regulator theorem- Friston et al,)
2)  The complexity of that systems model of the world: Given the energetic costs of maintaining (and/or updating) a model, a system's model should be "simple enough but no simpler" to regulate the system and describe (enough) of it's world
 

### Theoretical/Mechanical solve, and additional constraints + observationns
3)  The combination of 1 and 2 can be formally addressed by tools like Occam's Razor,  PAC learning Bayesian inference,  (Jaynes, Ortega and Braun) (Solomonoff's optimal inductive inference combines both, Hutter and Schmidhuber do fun stuff with minimimum descriptionn lengths and universal distributions:  Friston et al's free energy principal formalizes things nicely).

4) In the search for a "simple but effective" model, any locally adaptive (self organizing) system must necessarily compress "sense" data into simpler constructs.   That is, reduce (local) entropy- both in Shanon's information theoretic sense, but also in a physical sense of doing-work-to-maintain-a-far-from-equilibrium state (laplacian demons, bennnett's computational depth, Prigogine, see also Sengupta's 2012ish experimental work).
 We can think of this process as seperating a "useful" (entity-preserving-in-some-way) signal from associated environmental noise (not-worth-encoding or acting-upon).

5)  Such models are (very likely) (at least implicitly) hierarchical.  (If for no other reason than the need to capture at least 2 or 3 layers of hierarchically organized time-scales:

   * i.  The short-order time scale at which the system "observes" it's environment/ "external things happen".
   * ii.  The time scale of a single perception->-action loop and
   * iii. the timescale for encoding the results of multiple perception/action loops.
   * iv. (Embodied+Enactive cognition folks may not agree with this language- feel free to thinkn of this as a [nested series of tensigrity structures](https://pubmed.ncbi.nlm.nih.gov/12615960/) creating [markov blankets](http://philsci-archive.pitt.edu/18831/), allowing for feedback loops)


### Claim 2
### 1) Formalizing 1 - 5 can be done in terms of Friston's free energy principle.  (Bayesian learning, Active Inference, all that fun stuff)
2) A natural result of doing so, is the emergence of self-organized instability (Friston/Breakspear 2012) and symmetry breaking
   (For the relationn between Optimal Control and Bayes see Todorov: [General duality between optimal control and estimation](https://homes.cs.washington.edu/~todorov/papers/TodorovCDC08.pdf), and also [Todorov's efficient computation and control paper](https://www.pnas.org/doi/pdf/10.1073/pnas.0710743106)- For the relation of optimal control and symmetry breaking see:  [Path integrals and symmetry breaking for optimal control theory: Kappen](https://iopscience.iop.org/article/10.1088/1742-5468/2005/11/P11011/meta ).
3) Informally - this self organized instability can be thought of as organizing a system's "internal states" (those bounded by a markov blanket) into distinct basins-of-attraction (characterized by particular low-entropy macrostates)- switching between such states could look like binoculary-rivalry or bistable figures (in the case of perception: two equally likely (but incommensurate) hypotheses about the order of the world) or in the case of development this might mean switching between Piagatian phases (I'm partial to Ullman and Tenenbaum's annealing approach in "Theory learning as stochastic search in the language of thought").  Fun ways to think about why this particular form of organization is efficient/effective can be found in Stuart Kauffman (Investigations, and Origins of Order) and Langton's computation at the edge of Chaos.  Essentially, the idea is to have the widest possible array of internal-arrangements that map to predictable outcomes of external states,(possibly with a reservoir of additionnal possible arrangements for unknown/unknowable states - see Ulanowicz's degree of order work, on that specific questionn as well).
4) Self organized instability/symmetry breaking accounts for and is in evidence in behavior change, EEG signals (as phase transitions) in Insight Problem Solving. (Along the empirical lines presented in the (2009?) paper -
   "The Self Organization of Insight").


########################################

### Research program:
The research program for this work was as follows:  
1) masters: Use a suitably simple Bayesian-Free-energy model for reinforcement learning (Mathys's Hierarchical Gaussian Filter (HGF(- basically some really clever nested kalmann filters with coupled/variable learning rates) on a well established task (A Wisconsin Card Sort like reversal learning task) and A) test model fits, B) test if particular mathemetical parameters correspend to within-subjects-psychometric differences (e.g. hierchical coupling = cognitive flexibility/inhibition? learning rates relate to working memory)- (and maybe if ambitious also test physiological correlates of those between subjects differences + model parameter fit (e.g. eye blink rate and pupillometry)).
(The paper entitled 1st year project, in this repo, gets at this)
2) PhD - extend the self organization of insight work to a wider variety of insight tasks (the 9 Dot problem paper in this repo lays that out).
3) Post Doc or other - Theoretical: explore the intersection betweenn the mutual information measures in Ulanowicz's degree of order work with behavioral correlates of creativity.  Factor analysis on a battery of cognitive flexibility tasks.  Possible Explorations of Michael Leyton's Process Grammar/Generative theory of shape as a language-of-bayesian-thought?  Exploring Treves Latching networks from a bayesian control perspective?

### Unfortunately ....
A faculty member who I had trusted to advise me, plagiarized my work (after discouraging several publications) and retaliated when I addressed the issue - (including engaging in behavoirs that threatened funding, and created barriers to IRB approval for experimental work). After some time of languishing in academic limbo, I left for the private sector.

I still hack on this stuff in my free time, and am happy to collaborate with scholars or practitioners who want to reach out.  tim.sparer.professional@gmail.com

(Note: everything in this repo is original work from 2016 or earlier (with special thanks to Raphie Kaplan, Karl Friston, and Christoph Mathys for replies to emails regarding clarifications on model instantiations and free energy math, and massive thanks to Carlos Salas and Jared Ramsberg for experimental support)).  
My guess is that some folks have picked this kind of thing up since then, and or/were working in parallel.  Maybe I'll do some google searches and throw up a post on developments since then?)
