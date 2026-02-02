# Genome-Fingerprinting
A Budgeted Genome Fingerprinting and Agreement Scoring System that computes a compact fingerprint vector from genome-like sequence data and reports a numerical Fingerprint Agreement Score between two samples.

# Use
1. At start, proogram will ask the user to enter the DNA sequence for sample A, then for sample B
2. Then, it should ask the user to enter a budget value B
3. the program will clean the samples, and output the cleaned samples, computed maximun allowed recursion-tree depth,fingerprint for Samples, A and B, and the final Bray-Curtis based Fingerprint Agreement Score
4. Will Display the program outputs
   - the cleaned samples of A and B
   - computed maximun allowed recursion-tree depth
   - fingerprint for Sample A
   - fingerprint for Sample B
   - The final Bray-Curtis based Fingerprint Agreement Score

# How it Works
Two genome-like Dna sequences are entered directly by the user, one for Sample A and one for sample B. Each sequence is then processed using a divide and conquer recursion tree whose growth is explicitly controlled
the allowed number of recursion-tree levels is computed from a depth recurrence under a fixed budget B to ensure predictable scaling. The resulting fingerprints are compared using a Bray–Curtis-based Fingerprint Agreement Score, reflecting the broader family of alignment-free sequence analysis methods that rely on compact, count-based signatures for repeated, large-scale comparisons

# Requirements
The program must implement a fully functional Budgeted Genome Fingerprinting and Agreement Scoring System that adheres to the specifications below. The same program will be tested during grading using DNA sequences that may be substantially larger and may contain more noise, so algorithmic efficiency (efficient recurrence evaluation and budgeted recursion) is part of the required design. 
