# Prime-And-Logical-Operations
Functions that address prime-related puzzles or involve logical packing/unpacking operations.

Functions written by Dr Eleni Christoforidou in MATLAB.

## logiunpack

An n-by-n square logical matrix can be represented by a cell array of n elements where the kth element corresponds to the kth row of the matrix. Each element of the cell array is a row vector of positive integers in increasing order representing the column indexes of the logical true values in the given row of the matrix. All other elements in the given row of the logical matrix are false. The function takes such a cell array as input and returns the corresponding square logical matrix. For example, such a cell vector representation of a 100-by-100 logical matrix with the only true elements at indexes (10,20) and (10,75) would have only one non-empty element of the cell vector at index 10. That element is the vector [20 75].

## logipack

The function takes a square logical matrix as input and returns a cell array of n elements where the kth element corresponds to the kth row of the matrix. Each element of the cell array is a row vector of positive integers in increasing order representing the column indexes of the logical true values in the given row of the matrix. All other elements in the given row of the logical matrix are false. Note that empty array elements of the cell array corresponding to rows with all false values have a size of 0x0.

## eligible

The function decides whether a university applicant is eligible for admission based on GRE scores. The function takes two positive scalars called v and q as input. They represent the percentiles of the verbal and quantitative portions of the GRE respectively. The applicant is eligible if the average percentile is at least 92% and both of the individual percentiles are over 88%. The function returns the logical true or false.

## circular_primes

The function finds the number of circular prime numbers smaller than n, where n is a positive integer scalar input argument. For example, the number, 197, is a circular prime because all rotations of its digits (197, 971, and 719) are themselves prime. For instance, there are thirteen such primes below 100: 2, 3, 5, 7, 11, 13, 17, 31, 37, 71, 73, 79, and 97. Note that rotation means circular permutation not all possible permutations.
