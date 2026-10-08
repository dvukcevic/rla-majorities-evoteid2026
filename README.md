# Risk-Limiting Audits for Parliamentary Majorities

A talk presented on 8 October 2026 by [Damjan Vukcevic][damjan] at the
[11th International Joint Conference on Electronic Voting][evoteid2026]
(E-Vote-ID 2026).

[damjan]: http://damjan.vukcevic.net/
[evoteid2026]: https://e-vote-id.org/programme-2026/

Authors: Jack Freestone, Dennis Leung, Damjan Vukcevic.


## Abstract

Existing methods for risk-limiting audits typically focus on certifying
individual contests. In parliamentary elections, however, the politically
relevant outcome is often whether a party has won enough seats to form
government, not whether every reported seat outcome is correct. Extending on
the work of [Mohanty et al. (2019)](https://arxiv.org/abs/1901.03108), we
formulate the certification of a parliamentary majority as a partial
conjunction testing problem: it is enough to verify that the reported winning
party truly won at least a majority of its reported seats. Building on the
SHANGRLA auditing framework, we construct a sequential audit statistic for
the majority outcome by combining seat-level statistics. We then propose
adaptive sampling strategies that allocate auditing effort across seats,
including variants that learn to avoid spending excessive effort on seats
that appear unlikely to have been truly won. Using simulations based
on synthetic and real data, from the 2014 Indian Lok Sabha election, we
show that auditing the parliamentary majority can substantially reduce
the number of ballots inspected (by almost a thousand-fold) compared
to certifying every reported winning seat.


## Licence

[![Creative Commons License][cc-img]][cc]  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc].

[cc]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-img]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png