# Data Structures in Cairo
Just me playing with Cairo while learning about the language and implementing basic data structures.

## Motivation
Mainly to learn more about the language, but also to contribute so that there are more examples of the Cairo syntax (who knows, maybe someone uses this and finds it useful).

## What have we done so far?
### - [Lists](https://github.com/sdgalvan/data-structures-cairo/blob/master/src/list.cairo) 
**Notes**: 
I'm aiming to try to encapsulate functionality that complicates the user, for example always taking into account the length of the list. The trade-off is that we're constantly updating that variable in a dict and it's maybe a bit more expensive than a conventional implementation in Cairo, but I wanted to give you that approach as long as you keep this in mind.

#### Methods
```
- new_list()
- add(val: felt)
- get(idx: felt)
- remove(idx: felt)
- replace(idx: felt, val: felt)
- contains(val: felt)
- size()
```

Can see examples of use on the [list_test.cairo](https://github.com/sdgalvan/data-structures-cairo/blob/master/tests/list_test.cairo) (Using Protostar)
