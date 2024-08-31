
# Good Vs Evil
The exercise involves calculating the outcome of a battle between the forces of good and evil in Middle Earth. Each race on both sides has a specific "worth" or strength value
## Quick summary
Based on this CodeWars exercise I wrote a quick program that would calculate the worths and return certain strings.
### Good Side Races and Their Worth:
```
Hobbits: 1
Men: 2
Elves: 3
Dwarves: 3
Eagles: 4
Wizards: 10
```

### Evil Side Races and Their Worth:

```
Orcs: 1
Men: 2
Wargs: 2
Goblins: 2
Uruk Hai: 3
Trolls: 5
Wizards: 10
```

<br>
Return :

``` "Battle Result: Good triumphs over Evil" ```
if good wins, <br>
``` "Battle Result: Evil eradicates all trace of Good" ```
if evil wins, or <br>
``` "Battle Result: No victor on this battle field" ```
if it ends in a tie.

### Good Vs Evil - Testing

Using NUnit Legacy Framework I decided to copy-and-paste tests used in CodeWars to check locally if my program works correctly.

You can check the tests here => [GoodVsEvilTests](https://github.com/ArkadiuszTelega/FinishedProjects/blob/main/CodeWars/GoodVsEvilTests).
