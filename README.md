# How to use
Access https://dlgpdmsly2.github.io/latin-verb-conjugate/?verb=&tense=&person=

URL parameters:
* `verb`: 1st person indicative present form of the verb
* `tense`:

  |            | Active      |            | Passive     |  |
  | -------------- | ---------- | ----------- | ---------- | ----------- |
  |                              | Indicative           | Subjunctive            | Indicative           | Subjunctive            |
  | Present                      | 0                    | 1                      | 10                   | 11                     |
  | Imperfect                    | 2                    | 3                      | 12                   | 13                     |
  | Perfect                      | 4                    | 24                     | 14                   | 26                     |
  | Pluperfect                   | 9                    | 25                     | 19                   | 27                     |
  | Future                       | 5                    |                        |                      |                        |
  | Future perfect               | 6                    |                        |                      |                        |
  | Imperative                   | 8                    | 28                     |                      |                        |

  | Nominal forms* |    |
  | -------------------------- | -- |
  | Gerund                                               | 21   |
  | Gerundive                                            | 23   |
  | Present participle                                   | 22   |
  | Future participle                                    | 29   |
  | Perfect passive participle                           | 32   |
  | Infinitive                                           | 40   |

  \* These only return one string, so you do not have to assign a `person`. 

* `person`: a number between 0 and 5 in order of 1st, 2nd, 3rd person singular followed by plural.

The resulting conjugation is displayed inside `<p id='result-container'>`, which can be fetched by parsing the HTML. 

Hope this helps!

# References
* [Verbix API](https://api.verbix.com/conjugator/html)