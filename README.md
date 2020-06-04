# The Google billboard problem

## What does this mean?
The task was to find the first 10 digit prime number in the euler number.

## What was it used for?
Well, the sense of this was to attract people to a website of [Google](https://www.7427466391.com) to there solve another issue.
If you managed to solve both of the puzzles, you were invited to a job interview at Google.
Google simply wanted to find smart people, I guess.
Actually, the [website](https://www.7427466391.com) is now no longer online.

## The algorithm to solve the puzzle:
So first challenge: Where to get a ton of e digits? Our friends from the NASA help us out here: https://apod.nasa.gov/htmltest/gifcity/e.2mil (Thanks NASA for this :D)

What to do now? So, the algorithm is quite simple: Take the first 10 digits from the e digits and check if they're prime. If yes: finished, if no: Take the next 10.

So basically: e =

2.718281828459045235360287471352662497757247093699959574966
967627724076630353547594571382178525166427427466391932003059
921817413596629043572900334295260595630738132328627943490763
233829880753195251019011573834187930702154089149934884167509
244761460668082264800168477411853742345442437107539077744992
069551702761838606261331384583000752044933826560297606737113
200709328709127443747047230696977209310141692836819025515108
657463772111252389784425056953696770785449969967946864454905
987931636889230098793127736178215424999229576351482208269895
193668033182528869398496465105820939239829488793320362509443
117301238197068416140397019837679320683282376464804295311802
328782509819455815301756717361332069811250996181881593041690
351598888519345807273866738589422879228499892086805825749279
610484198444363463244968487560233624827041978623209002160990
235304369941849146314093431738143640546253152096183690888707
016768396424378140592714563549061303107208510383750510115747
704171898610687396965521267154688957035035402123407849819334
321068170121005627880235193033224745015853904730419957777093
503660416997329725088687696640355570716226844716256079882...

We take firstly: 	7182818284 --> Is it prime? --> No

Next step: 			1828182845 --> Is it prime? --> No

...

Last step: 			7427466391 --> Is it prime? --> Yes :D

## How to calculate primes efficiently?
https://en.wikipedia.org/wiki/Primality_test

What I used for this is the pseudo-code example here: https://en.wikipedia.org/wiki/Primality_test#Pseudocode


## Where is the result in e?
2.718281828459045235360287471352662497757247093699959574966
96762772407663035354759457138217852516642**7427466391**932003059
921817413596629043572900334295260595630738132328627943490763
233829880753195251019011573834187930702154089149934884167509
244761460668082264800168477411853742345442437107539077744992
069551702761838606261331384583000752044933826560297606737113
200709328709127443747047230696977209310141692836819025515108
657463772111252389784425056953696770785449969967946864454905
987931636889230098793127736178215424999229576351482208269895
193668033182528869398496465105820939239829488793320362509443
117301238197068416140397019837679320683282376464804295311802
328782509819455815301756717361332069811250996181881593041690
351598888519345807273866738589422879228499892086805825749279
610484198444363463244968487560233624827041978623209002160990
235304369941849146314093431738143640546253152096183690888707
016768396424378140592714563549061303107208510383750510115747
704171898610687396965521267154688957035035402123407849819334
321068170121005627880235193033224745015853904730419957777093
503660416997329725088687696640355570716226844716256079882651

## Implementations
[Java](https://github.com/SeppPenner/TenDigitPrimeCalculatorJava)

[Scala](https://github.com/SeppPenner/TenDigitPrimeCalculatorScala)

[C#](https://github.com/SeppPenner/TenDigitPrimeCalculatorCSharp)

[Python](https://github.com/SeppPenner/TenDigitPrimeCalculatorPython)

## The result
7427466391 or https://www.7427466391.com

## References
http://franzhuber23.blogspot.de/2017/10/google-10-digit-prime-in-eulers-number.html

http://explorepdx.com/firsten.html

https://mkaz.blog/math/google-billboard-problems/

https://apod.nasa.gov/htmltest/gifcity/e.2mil

http://aleembawany.com/2004/07/20/google-billboard-puzzle-the-lazy-way/

http://mathworld.wolfram.com/news/2004-10-13/google/

https://www.seroundtable.com/archives/000644.html

http://www.businessinsider.com/what-google-can-teach-us-about-solving-problems-2011-7?IR=T

https://www.mkyong.com/java/how-to-determine-a-prime-number-in-java/

https://en.wikipedia.org/wiki/Primality_test

https://en.wikipedia.org/wiki/Primality_test#Pseudocode

Change history
--------------

See the [Changelog](https://github.com/SeppPenner/SolvingTheGoogleBillboardProblem/blob/master/Changelog.md).
