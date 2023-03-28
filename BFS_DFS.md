Implemented DFS and BFS algorithms provided in Cormen's 'Introduction to algorithms' for undirected graphs.
It wasnt supposed to be optimal or short solution but rather implementation of specific version of these algorithms so it displays states of enqueueing etc.

Firstly, program runs DFS and shows every step of checking nodes. Black color of node means that there is no more depth in it and thus its a leave.
Next, it runs BFS. 

It also check whether graph is a Tree, Forest, Cyclic Graph or we have cyclic graphs. 
It checks connectivity by doing DFS-like algorithm and appends visited node on list, if that list equals the list of V, it is connected.
It check cycles by recursive checking 'neighbours' of node, if node has been visited - it appends id of that node on another list;
next, if neighbours of that node are already on that list, it checks if the neighbour is his predecessor, if no, we have detected a cycle.