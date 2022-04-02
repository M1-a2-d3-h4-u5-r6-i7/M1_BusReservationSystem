# HIGH LEVEL TEST PLAN
| TEST ID |                            DESCRIPTION                            | EXP I/P           | EXP O/P                    | Actual o/p                 | Type Of Test |
|:-------:|:-----------------------------------------------------------------:|-------------------|----------------------------|----------------------------|--------------|
| HR01    | chech if the available bus in a system properly                   | proper  execution | formatted bus list page    | formatted bus list page    | Requirement  |
| HR02    | check if the number seats available seats menu displayed properly | proper  execution | formatted menu page        | formatted menu page        | Requirement  |
| HRO3    | check if the passengers name displayed properly                   | proper  execution | formatted name list        | formatted name list        | Requirement  |
| HR04    | chech if the seats are booked properly                            | proper execution  | formatted booked tickets   | formatted booked tickets   | Requirement  |
| HR05    | check if the passengers ticket details are displayed properly     | proper execution  | formatted details page     | formatted details page     | Requirement  |
| HRO6    | check if the seats are properly allocated                         | proper  execution | formatted seats allocation | formatted seats allocation | Requirement  |
| HRO7    | check if the tickets are cancelled properly                       | proper  execution | formatted cancel page      | formatted cancel page      | Requirement  |
| HR08    | check if the user information displayed properly                  | proper execution  | login credebtials          | login credebtials          | Requirement  |


# LOW LEVEL TEST PALN
| TEST ID |            DESCRIPTION           | EXP I/P        | EXP O/P                                                  | Actual o/p                                               | Type Of Test |
|:-------:|:--------------------------------:|----------------|----------------------------------------------------------|----------------------------------------------------------|--------------|
| LR01    | verify number of available bus   | bus name       | name present->available; name absent->not found          | name present->available; name absent->not found          | Technical    |
| LR02    | verify number of available seats | seat number    | name present->available; name absent->not found          | name present->available; name absent->not found          | Technical    |
| LR03    | verify passengers names          | passenger name | name present->verified; name absent->not verified        | name present->verified; name absent->not verified        | Technical    |
| LR04    | verify booked seats              | seat number    | name present->verified; name absent->not verified        | name present->verified; name absent->not verified        | Technical    |
| LR05    | verify passengers ticket details | ticket number  | name present->verified; name absent->not verified        | name present->verified; name absent->not verified        | Technical    |
| LR06    | verify seats allocations         | seat number    | if entry present->allocated seats; else->not allocated   | if entry present->allocated seats; else->not allocated   | Technical    |
| LR07    | verify the ticket cancellation   | ticket number  | if entry present->cancelled; name absent->not cancelled  | if entry present->cancelled; name absent->not cancelled  | Technical    |
| LR08    | verify user credentials          |                | if entry present->display them; else->display empty file | if entry present->display them; else->display empty file | Technical    |

