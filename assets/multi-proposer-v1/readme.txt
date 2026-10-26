Multi-seed controller-search replication: public evidence

Study: multi-proposer-v1, benchmark synthetic-pid-v2. Five model searches,
five random searches, one deterministic coordinate-search path.

The article is the reviewed interpretation. registered-protocol.txt and
frozen-benchmark.json preserve historical registration bytes. Their planned,
not-run, mock and disabled-execution labels describe registration defaults,
not the completed study. The protocol's stronger reliability language is a
hypothesis, not a general conclusion. No source-code reproduction package is
included in this website release.

evidence.json supplies full-precision selected-controller measurements,
primary intervals and source-summary hash. holdout-rollouts.csv contains
1,440 logical trial rows, representing 990 distinct physical evaluations;
duplicate controllers reuse measurements. Group by method/repetition and
seed, averaging all three regimes, before computing comparison statistics.
Raw tracking, effort and slew columns have objective weights 1, 0.01 and
0.05; unsafe fraction has weight 10. Do not treat repeated rows as independent.

budget.csv supplies development search curves; costs.csv supplies selected
controller development/holdout and regime costs. PNGs are the three reviewed
diagnostic figures. The separate illustrative trajectory bundle is not
included; it contains 15 development and 15 holdout examples.

Primary inference uses 10,000 crossed paired bootstrap samples, seed 4100,
resampling five repetition indices and 30 holdout noise-seed blocks with
replacement. Two-sided 97.5% intervals implement the registered Bonferroni
adjustment for two primary comparisons. Five searches limit precision.
Holdout seeds 5000..5029 have already been inspected and are locked.
