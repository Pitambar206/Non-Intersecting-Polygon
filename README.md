## Non-Intersecting-Polygon
## Algorithm:

Find the leftmost points p
Find the rightmost point q
Partition the points into A, the set of points below pq, and B, the set of points above pq [you can use the left turn test on (p,q,?) to determine if a point is above the line].
Sort A by x-coordinate (increasing)
Sort B by x-coordinate (decreasing).
Return the polygon defined by p, the points in A, in order, q, the points of B in order.
