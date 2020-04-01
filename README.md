# Treap-Data-Structure
a data generator, a randomized treap and a simple competitor


The Data Generator:  
  * gen element():  
    return element (id, key);  
  gen insertion():  
    return an insertion for x;  
  gen deletion():  
    •if the element x with iddel has already been deleted,return a deletion for deleting the search key keydel;  
    •otherwise, return a deletion for deleting the search key x.key, i.e., the search key of x;  
  gen search():  
    return a search operation with search key q;  

The Randomized Treap:  
  insert(x):  
  delet(keydel):  
  search(q):  
    return an arbitrary element (if it exists) that has a search key key = q; otherwise,  
    return NULL.  

The Competitor:  
  insert(x):  
  delete(keydel):  
  search(q):  
