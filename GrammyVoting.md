# Grammy Voting
Cleaning Up Grammy Voting

EXCEL
valid: 931
invalid: 102
Total: 1033

SENDINBLUE
Not Blacklisted: 875
Blacklisted: 157
Total: 1032 (edited)

----
valid 931 - not blacklisted 875 = 56
invalid 102 - blacklisted 157 = -55 (edited)

---
Create Grammy Voting Copy to sync Blacklisted between Excel & Sendinblue

Imported [102] *invalid to [157] *blacklisted
>--message = [102] existing contacts across all lists--<
*blacklisted now = [157] existing, [28] new = [185]

[185] *blacklisted now in $Grammy Voting*
[847] not *blacklisted now in $Grammy Voting*

>-- Deleted 'Grammy Voting Copy used to sync above--<

# YES @GrammyVoting = [1032] after Blacklisted clean up
*[185] blacklisted + [847] notblacklisted = [1032] in @GrammyVoting!*

---
Sync Valid & Not Blacklisted
{copied list}
Imported [932] *valid to [847] *NotBlacklisted
>--message = [927]existing [1]duplicate [3]new contacts across all lists--<
*blacklisted [82]
*notblacklisted [850]
*total [931]
{Deleted Duplicates 'In This List'(copied voting list)}
*now only 3 in total, not blacklisted [3 new?]
{Deleted 'cdbaby@cdbaby.com}
*now only 2 in total and new

{added these 2 to original Grammy Voting list}
*blacklisted still[185]
*not blacklisted now[849]

# YES @GrammyVoting = [1032] after NotBlacklisted clean up
*[185] blacklisted + [849] notblacklisted = [1034] in @GrammyVoting!*
*2 new*

# @GrammyVoting Now Clean
