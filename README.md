This example demonstrates a common, yet subtle, error in Perl when iterating over hashes. Perl does not guarantee the order in which keys are returned by the keys function.  The bug.pl file shows this unexpected behavior. The bugSolution.pl file offers a solution using a sorted iteration.