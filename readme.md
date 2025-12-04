in searching
curr strategy:
    - search via title via hashtable

modify it to:
    - search via title via hashtable
    - search via artist via avl

known unavoidable problem:
    -when you click on the song after searching, it is not going to open that song

Mitigate it using:
    - a seperate vector<Song*> curr to store which songs are displayed
    - use it to play the correct song
