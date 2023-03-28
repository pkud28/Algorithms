Code creates Red-Black Tree. It implements algorithms provided in Cormen's 'Introduction to Algorithms'.

From list of nodes it adds nodes step by steps checking rules of RB tree and fixing it on the run.

Rules:
1. every node is either black or red
2. root is black
3. every leaf (nil) is black
4. if node is red, both of his sons are black
5. for each node, all simple paths from the node to descendant leaves contain the same number of black nodes