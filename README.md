# Computational-Statistics
A hands-on course in applied statistics with SAS covering the full data analysis workflow. Topics included implementing algorithms, MCMC simulations, random data generation, data exploration, descriptive statistics, and formal hypothesis testing.

Monte Carlo or for short MC is a procedure which uses random numbers, and by random numbers we think about numbers who have no sort of connection with other numbers in that queue. Pseudo-random number are those that we generate with computer's algorithams so they seem random (but really they aren't). Those alorithams are dictated by "seed" or the initial state of the program. 

J.Von Neumann - Middle-mean aloritham: (...)

Lehmer - Linear congruent method: (...)

IBM - popular generator RANDU: (...) with him we get pseudo-random number which follow discrete uniform distribution on set S={1,2,...,2^31 -1}

Which are the necessery properties of a "good" uniform generator od random numbers?
uniform marginal distribution, repetitionary, fast calculating...
There are a lot of statistical test and empirical test that have first to properties, for example:
 DIEHARD (http : //www.staff .science.uu.nl/ ∼sleij101/Opgaven/LabClass/site/asm diehard.php)
(MarsagliaRN CDROM i DIEHARD battery of tests of randomness, 1985, 1995)
NIST Test suite (2000), (http : //csrc.nist.gov/groups/ST/toolkit/rng/documents/SP800 − 22b.pdf )
