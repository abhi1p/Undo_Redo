**Implementation of Undo/Redo**    

How to install:-  
`pip install Undo-Redo`  

UndoRedo class contains following functions:-
1. `append()`  
    It will append data into stack.
2.  `pop()`  
    It will pop data upto current index.
3.  `undo()`  
    It decreases the current index.
4.  `redo()`  
    It increases the current index.
5.  `undoText()`  
    Returns data of (current index-1). It can be used before `undo()`.
6. `redoText()`  
    Returns data of (current index+1). It can be used before `redo()`.
7.  `undoAvailable()`  
    Return True if undo is possible.  
8.  `redoAvailable()`  
    Return True if redo is possible.  
9.  `out()`  
    Returns stack as list.

Example:-  
`from Undo_Redo import UndoRedo` module import  
`stack=UndoRedo()` create object