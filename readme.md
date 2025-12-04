current:
    hashtable is made from unordered_list stl template

modify it to:
    declare hashtable class in data_structure.h
    -26 vector<DLLNode*> buckets
    -hashing is done on basis of first character of title
    -Each node added to its appropriate bucket at the time of initialisation
    -search(std::string query) will return vector<Song*> searched wrt title  
