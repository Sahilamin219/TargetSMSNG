

It can be established that the rows that become 1 in the end are same in the beginning. So, keep a count of the frequency of every distinct row and since we have to perform exactly k operations, find the row with maximum frequency and (noOfZeros — k)%2 == 0. The answer is the frequency of that row.
