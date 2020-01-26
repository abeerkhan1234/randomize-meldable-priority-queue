We present a practical meldable priority queue implementation. All priority queue operations are very simple and their logarithmic
time bound holds with high probability, which makes this data structure
more suitable for real-time applications than those with only amortized
performance guarantees. Our solution is also space-efficient, since it does
not require storing any auxiliary information within the queue nodes.
we present a randomized approach to the problem of efficient
meldable priority queue implementation. The operations supported by this data
structure are the following [10]:
MakeQueue returns an empty priority queue.
FindMin(Q) returns the minimum item from priority queue Q.
DeleteMin(Q) deletes and returns the minimum item from priority queue Q.
Insert(Q, e) inserts item e into priority queue Q.
Meld(Q1, Q2) returns the priority queue formed by combining disjoint priority
queues Q1 and Q2.
DecreaseKey(Q, e, e0
) replaces item e by e0 in priority queue Q provided e0 ≤ e
and the location of e in Q is known.
Delete(Q, e) deletes item e from priority queue Q provided the location of e
in Q is known.
