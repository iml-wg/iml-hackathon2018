# Which ML tools / algorithms / frameworks support negative per-event weights

TODO: link to splot paper

# Toolkits

Toolkits may or may not have per-event weight support on the framework level:

| TMVA                 |    scikit-learn         | Neuro-Bayes        |  Keras    |   ... |
| -------------------- | ----------------------- | ------------------ | --------- | ----- |
|        ✓             |                         |                    |           |       |

# Methods

## TMVA

TMVA (possibly due to the HEP background) has per-event weights built-in. Still
for some MVA methods, they make no sense, are unapplicable. It is therefore
worth checking on a method-by-method basis

### BDT

#### AdaBoost

AdaBoost by design deals with per-event weights. TMVA combines the boosting
weights with the per-event weights by multiplying. The only headache is to make
sure boosting of minus signs boosts "in the right direction".

The actual implementation offers a few options how to deal with negative weights


## scikit-learn

My impression is that scikit learn was not designed with per-event weights in
mind, but that doesn't prevent individual methods to still deal with per-event
weights.

## Neuro-Bayes

Neuro-Bayes supports sWeights since quite a while and is (to my knowledge) the
only framework where a general statement "TOOL supports sWeights" is applicable
*and correct*.
