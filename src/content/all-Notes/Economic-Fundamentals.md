I'm trying to make a puzzle of puzzles rn but tbh its quite puzzling.


The fundamenatls include:
* Entities

Bitcoin is the abstract Thing. 
- Not Physical but Digital; it's own Financial System.
- It an Asset, A Currency, and the Central Market. 

* Value & Utility

* Time

You have split Time.
- Current Time exists in the choosing actions part of the state diagram in Value & Utility. This could go on forever.
- Future Time is in the future.
  - There are infinite futures but only comes true.
  - This would be where Keynes described as investing for precision. 
  - While winning bets the smaller the size of the set of futures bet on bigger the payoff the bet wins.

* Sin
* Money & Debt

Entities is the bedrock of the model. Humans and Things are the simplest elements.
Each fundamental adds complexity to Humans and Things.
When creating the model take it one fundamental at a time. Add complexity and Interactions but only one fundamental at a time. 


# ENTITIES:
### TERMS:
- "Humanity" : all Human's
- "CoH" : "a Combination of Humans".
  - This would be a combination of Humans between size 2 and (N-1) where N is the total number of Humans
- "CsoH" : "Combinations of Humans".
  - This would be k number of combinations of Humans between size 2 and (N-1) where N is the total number of Humans
- "Any Split Of Humanity" : any CoH, any Human, or Humanity.
- "Any Smaller Split of Humanity" : Any CoH, any Human. Not Humanity.


### CORE:
- Humans & Things
  - Humans
    - This exists on a spectrum of Singular to Whole.
      - Singular: Lisa, Kevin, etc
      - Group of n: {Lisa, Kevin, Angelina}, {Lisa, Kevin}, {Brad, Lisa, Angelina}, etc
      - Whole: Humanity
    - Assume Humans don't sin. 
      - Tragedy of the commons or publics is not possible.
      - This means individual ownership of Things is unneeded. 
        - Creating individual ownership of Things would be the utility of society.
      - Any Human would care more about the whole than of the singular. 
        - The biggest Utility Maximizing Decision wins.
    - Humans are 100% rational and thus _Any Split Of Humanity_ will choose to act rationally.
    - Can not be divided past 1 human. THIS IS DISCRETE
  - Things
    - Either things are discrete or they are continuous. You would need to think about it both ways.
    - Split into two:
      - Base Things
      - Combined Things

    - Are the principle building blocks of the world. (for now just assume they are all the elements)



    - Again this exists on a spectrum of Singular to Whole. CoT is Combinations of Things.
      - Singular: a chair, a bed, a cat, a dog, a "unit" of bread, etc
      - Group of n: {1 "unit" of rice, 1 "unit" of pork , 1 "unit" of broccoli}, {a bed, 4 walls, a roof, a door}, {Brad, Lisa, Angelina}, etc
      - Whole: The Community Chest
    - These are just things; not much to explain.
      - Chairs, Tables, Houses
      - Food, Water
      - Dogs, Cats
    - The total set of Things can be divided with an infinite number of reasons.
  - Relationship
    - Humans (society) owns all Things. 
    - No one Human "owns" any Thing. 


# VALUE & UTILITY:
TODO: Take notes from the presentation you made.

### VALUE & UTILITY + ENTITIES:
- Entities:
  - Things have Value and give Utility to Humans
  - Humanity owns all Things and thus owns all Value
  - No one Human "owns" any Thing and thus no one Human "owns" any Value

- Value & Utility:
  There is an Objective and Subjective split for Value and Utility. 
    - Terms:
      - O&S is Objective and Subjective
      - OV is Objective Value
      - SV is Subjective Value
      - OU is Objective Utility
      - SU is Subjective Utility
  - The Objective side is know by God
    - We could hypothetically "do the math"
      - It would require a really small amount of Things to find OV
      - It would require a really small amount of Things and Humans to find OU
  - The Subjective side is created by the CoH doing the subjecting.
  - Complexity:
    - There is 1 OV per Thing
    - There is 1 SV per Combination of (Thing + CoH)
      - This will have an error in approximation. Hyptothetically SV and OV could be equal but in the real world I doubt it.
    - There is 1 OU per Combination of (Thing + CoH)
    - There is 1 SU per (Combination of (Combination of (Thing + CoH)) and CoH).
      - This is just OU being "subjected" by every possible CoH.


OV:
- Has lots of dimensions to what it is:
  - Overall value unit.
  - The relationships between each Thing.
  - How many of each Thing society owns.
  - Total value units for each Thing.
I think this is "a progression". I thinks a whole number, then a 1-D matrix, then a 2-D matrix, etc

SV:
- Subjective is created from a "value function".
  - This will obviously have an error. SV and OV could theoretically be the same but in the real world never. 



Because we don't have time for now we will see how the model works with random states. 

(1) For now in this model we only have Entities and Value & Utility. Remember that because Humans don't Sin any Human would care more about the whole than of the singular.

1. At the beginning of a state we will see all Humans, all Things and OV, OU, SV, SU for all Things and CoT.
2. All Humans can see all OU & SU information from all other Humans.
3. Humans will make the decision to maximize Humanity's Utility. Where Humanity's Utility is equal to the sum of all Human's and CoH's end state Utility. (where NULL = 0)
  * Not all CoHs or Humans will have Utility at the "end" of the state. They will end up with NULL Utility.
4. A Human, a CoH, or Humanity can consume a Thing or CoT to gain Utility. The Utility gained by the Human, CoHs, or Humanity is the OU offered by the Thing or CoT for the Consuming Human(s).

(2) This is a simple algorithm. Given any input you can find the output and order of actions taken.
Let's add complexity. Now Humans only know a certain amount of SU from all other Humans. For now we shall say that "certain" is a random amount.

1. At the beginning of a state we will see all Humans, all Things and all OV, OU, SV, SU for all Things and CoT.
2. Each Human now sees _certain_ OU & SU information from all other Humans.
3. All Humans will make the rational decision to maximize Humanity's Utility. Where Humanity's OU is equal to the sum of all Human's and CoH's end state Utility. (where NULL = 0)
  * Not all CoH or Humans will have Utility at the "end" of the state. They will end up with NULL Utility.
4. A Human, a CoH, or Humaniyu can consume a Thing or CoT to gain Utility. The Utility gained by the Human, CoHs, or Humanity is the OU offered by the Thing or CoT for the Consuming Human(s).

This is the same as (1) except Humanity, any CoH and any Humans will have a chance at a lower ending Utility.
A single or multiple non U maximizing decision(s) will have been made. 
If the decision was a non U mazimizing decision than any Human or CoH affected by the decision taking or not taking place will now have a lower utility.

(3) This a bit closer to reality but just not there. Let's add in 






TODO:
- Go through the Terms create in Entities and make sure they are fully used. 
- Finish this state diagram. 
  - Right now you want to add a step between (1) and (2) which removes OU about Humanity from the knowledge base. 
  - Then you create the function of Humanity's ending Utility being the sum of all smaller splits of humanity.
  - You may want to copy/pase this state diagram to its own .md file.











# TIME:
Now essentially you would be describing a theoretical communist society. All decisions help the majority.

VALUE WITH TIME:
OV:
- Creative destruction is adding a new P that does something an old P did but better.
  - New P has more value than old P did when new P didn't exist.
  - Old P loses value when new P is created.
  - Thus when creative destruction occurs OV increases, old Ps lose value, and new Ps gain value.
OU:
- It's hard to estimate long term Utility gained or lost from an action. 
  - Especially for a long term negative consequences like if a society lost access to a resource because it went extinct (a cycle Thing that collapsed to zero)



Because Humans do not sin any CoH will choose to make the rational decision.
This will make it so there will never a cause where a Thing or CoTs would go extinct(1) if the Thing is definatively finite. You will never have a tragedy of the commons.


Piecewise function for Supply of T (or CoT): 
S(Thing) = Supply of (Things or CoT)         ΔS(Thing) = Change is the Supply of Things (or CoT)

S(Thing, Time + 1) = S(Thing, Time) + ΔS(Thing, Time)           if S(Thing, Time) != 0
S(Thing, Time + 1) = 0                                          if S(Thing, TIme) == 0




(1) I guess technically you could have a scenario where Humanity finds a Resource that is finite (x amount of units) but Humanity would only learn it is finite or how many units of that Resource exists when consuming (y amount of grams). Given x > y.


# SIN:

* Sin now adds Societies to Humans.
  * When doing the State Diagrams Society will a level of cohesion. Cohesion if your chance or modifer to care about the whole rather than the individual and vice versa.
  * Societies compete against each other. And can die.
* SV doesn't matter until Sin is considered. 
* Because Sin taints Humans you can now have a tragedy of the commons and publics.
* Humans may now prefer to only consume without producing. 
  * Humans now need to create Private Property. 
    * Because Private Property exists now Debt needs to exist.
    * Because Private Property exists now Money needs to exist. How do you know who owns what?
      * Because Money exists you now have a financial system.
  * The Community Chest is now off limits. Who can trust who?



Tragedy of Commons and Publics:

Before Sin:
  Because Humans do not sin any Human or CoH will choose to make the rational decision.
  This will make it so there will never a cause where a Thing or CoTs would go extinct(1).

After Sin:
  Because Humans sin any CoH have a chance to make an upward and a (repricol chance) downard consumption.
  Upward consumptions favor the whole. Downward consupetions favor individual.

  - No Human would prioritize it's self over the whole given the opportunity.
    - This would lead to an inherient social contract. 


1. Tragedy of the commons is when one generation of people consumes more than can be replenished.
  - Individuals in society casuse this tragedy

  - Humans will at times prioritize themselves over a "greater good". 
    - This leads to the social contract which didn't exist before to now exist. 
    - The social contract will also degrade over time. 
      * I have no clue how the "wave" function would act. Would Individuals and Societies both have a cohesion level?
    - When a Human prioritizes consuming a would be extinct Thing over any other split of Humanity optimal goal of not consuming. (not consuming it thus no extinction)


2. Tragedy of the publics is when Society consumes too much of a Thing than it should even if there is no extinction threat.
  - Like mindless art, funko pops, etc
  - Plastic is a great example. No short term extinction threat but there is posibly one long long off. 
  - This can also take place when society has too much abstract demand pulled forward in time by debt.
    - Future society is worse off because they will have less demand than it should. 
      - This creates waves. Someone has a job based on a Thing but looses it when that Thing loses demand.
        - Leads to recessions and depressions. 
        - "Are Depressions a thing of the past?"; well no, because The Rate set in your Financial System keeps going to Cheap Money
        - Cheap Money creates lots of short term demand. ("Ghost Demand" in the present and "Savings"*. *Include Default Risk!!!!)
      - Hypothetically it's a massive drop in demand. A "Cliff" persay:
        - At this point it may be better to drop all current financial systems overnight in favor of new ones. 
        - The new system would be incredibly hard to have mass adoption. 
        - It would require a plan (PR, SpokesPeople, etc)

What ever Things or CoTs can go fully extinct now need a market because of the Tragedy of the commons.
Because there is a tragedy of the publics. Society now needs temporal supply and demand markets or a strict social system.



# MONEY: 

Again the Community chest is off limits. 
Who can trust who? Which means we now must start using private property. 
Defined private property is really hard to trade. 
Money is created as a representative of abstract value. This removes the double coincidence of wants from society and thus ditches the barter system.


- We can create a universal numeraire for each Thing. 
  - This is Money
  - Money is a representation of Value. 
    - Society views it as an abstract form of Value. 
    - This allows for barter to succeed. 
    - No longer need the double coicidence of wants as both parties will always want abstract value. 
  - Money will always perfectly represent subjective value, but, in the real world, will never perfectly represent objective value.

Humans have a financial allegiance to the Currency they use.
Reserve Currencies are the true allegiance for Humans.
  No European has allengiance to the Euro. They have allengiance to the USD.




































# Economics:

Summary of each section:
### Value:
$ Only have Things for now. Add Services later in Time (they require time). 

### Entities:

### Time:

$ Services are temporal trades.
    Turn objective value into 


# Finance:

Summary of each section: 
#### Money & Debt:

### Supply & Demand:

### The Business Cycle:

