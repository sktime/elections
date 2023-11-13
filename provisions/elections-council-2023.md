# Provisions for sktime council elections 2023

## Seats and voting algorithm

### Seats and tenure

* the 2023 sktime council elections are for all seven council seats
* three seats are elected by the current council
* four seats are elected by the general electorate (contributors)

There are three shifted cohorts, cohort A, B, C.
Ultimately these cohorts are planned for 3 years tenure.

As these are the first sktime elections, some cohorts have shorted tenure to enable future shifting.

Seats are filled in this order:

1. cohort C, 3 years tenure, by current council
2. cohort C, 3 years tenure, by general electorate
3. cohort B, 2 years tenure, by current council
4. cohort B, 2 years tenure, by general electorate
5. cohort B, 2 years tenure, by general electorate
6. cohort A, 1 year tenure, by current council
7. cohort A, 1 year tenure, by general electorate

### Vote tallying algorithm

Each voter from the general electorate fills in four polls:

* selecting top preference from all candidates
* selecting top 2 preferences from all candidates
* selecting top 3 preferences from all candidates
* selecting top 4 preferences from all candidates

Each voter from the current council fills in three polls:

* selecting top preference from all candidates
* selecting top 2 preferences from all candidates
* selecting top 3 preferences from all candidates

Votes are tallied as follows:

Proceed with the seats ordered as above, 1-7.

1. consider the the open seat with lowest number.
  Let n be its order for the group determining the seat (council or general electorate),
  this will be an integer, between 1 and 4.
  Find the candidate with most mentions in the top n preferences vote of that group.
2. check exclusion criteria for the candidate. If not met, seat the candidate.
  Eliminate the candidate from further seatings, in any case.
3. Goto 1 until no more seats or candidates remain.

Proceed with the four general electorate seats, using the same algorithm.

### Exclusion rules

* a candidate of a primary affiliation that is already present on the council or has filled a seat cannot be elected. The same holds for a primary affiliation that is the same up to significant individual or institutional dependency relation such as >50% owned subsidiaries, or a substantial conflict of interest relationship.

* at least 1/3 of the seats must be filled by candidates eligible through code contributions; at least 1/3 of the seats must be filled by candidates eligible through community contributions. If a seat assignment would make this impossible, the candidate cannot take the seat. If there is no possible seat assignment satisfying the above to start with, the 1/3 should be replaced by the largest possible fraction smaller than 1/3.

## Eligibility

### Eligibility to vote

i. voter registration completed in time
ii. contributor with any contribution registered in `allcontributor-src`
iii. not subject to an active full ban or relevant code of conduct sanction at the voter registration cutoff


### Eligibility to be elected

i. candidates must be eligible to vote
ii. contributor with at least a "substantial" code or community contribution as defined in contribution requirements document
iii. candidates must have registered in time
iv. candidates must have submitted a candidate statement with their registration, intended for publication
v. candidates must have truthfully declared their full name, primary affiliations, and any conflicts of interest in their candidate statement


TODO: link contributions doc in appropriate places
