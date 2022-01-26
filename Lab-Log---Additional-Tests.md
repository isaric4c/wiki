| Variable / Field Name | Section Header          | Field Type | Field Label                                                                | Choices or Calculations                       |
| --------------------- | ----------------------- | ---------- | -------------------------------------------------------------------------- | --------------------------------------------- |
| add\_blood\_date      |                         | text       | Date                                                                       |                                               |
| haema\_done           | Haematological Profile  | checkbox   | Please tick all tests that have been DONE                                  | 1, Folate ; 2, Vitamin B12 ; 3, Iron ; 4, LDH |
| folate\_less\_greater |                         | dropdown   | Folate - Select if test result provided is not an exact value              | 1, < (Less than) ; 2, > (Greater than)        |
| folate                |                         | text       | Folate - Result (μg/L)                                                     |                                               |
| folate\_other\_unit   |                         | text       | Folate - If using a different unit other than μg/L                         |                                               |
| b12\_less\_greater    |                         | dropdown   | Vitamin B12 - Select if test result provided is not an exact value         | 1, < (Less than) ; 2, > (Greater than)        |
| b12                   |                         | text       | Vitamin B12 - Result (ng/L)                                                |                                               |
| b12\_other\_unit      |                         | text       | Vitamin B12 - If using a different unit other than ng/L                    |                                               |
| iron\_less\_greater   |                         | dropdown   | Iron - Select if test result provided is not an exact value                | 1, < (Less than) ; 2, > (Greater than)        |
| iron                  |                         | text       | Iron - Result (μmol/L)                                                     |                                               |
| iron\_other\_unit     |                         | text       | Iron - If using a different unit other than μmol/L                         |                                               |
| ldh\_less\_greater    |                         | dropdown   | LDH - Select if test result provided is not an exact value                 | 1, < (Less than) ; 2, > (Greater than)        |
| ldh                   |                         | text       | LDH - Result (U/L)                                                         |                                               |
| ldh\_other\_unit      |                         | text       | LDH - If using a different unit other than U/L                             |                                               |
| tft\_done             | Thyroids function tests | checkbox   | Please tick all tests that have been DONE                                  | 1, TSH ; 2, Free thyroxine (T4)               |
| tsh\_less\_greater    |                         | dropdown   | TSH - Select if test result provided is not an exact value                 | 1, < (Less than) ; 2, > (Greater than)        |
| tsh                   |                         | text       | TSH - Result (miu/L)                                                       |                                               |
| miu\_other\_unit      |                         | text       | TSH - If using a different unit other than miu/L                           |                                               |
| t4\_less\_greater     |                         | dropdown   | Free Thyroxine (T4) - Select if test result provided is not an exact value | 1, < (Less than) ; 2, > (Greater than)        |
| t4                    |                         | text       | Free thyroxine (T4) - Result (pmol/L)                                      |                                               |
| t4\_other\_unit       |                         | text       | Free thyroxine (T4) - If using a different unit other than pmol/L          |                                               |
| other\_done           | Other                   | checkbox   | Please tick all tests that have been DONE                                  | 1, SARS-Cov-2 Serology                        |
| sars\_cov2\_result    |                         | radio      | SARS-CoV-2 Serology - Result                                               | 1, Positive ; 0, Negative ; 2, Indeterminate  |
| covid19               |                         | text       | SARS-Cov-2 Serology - Result (Legacy field)                                |                                               |