## List(mutable)
List is a mutable container that can hold any type of data objects, and these objects are ordered.

## Tuple(immutable)
Tuple is an immutable sequence that can contain any type of data. The elements are separated by commas and are commonly used to protect data from modification.

| Category | Operation | Example | Input | Output |
|----------|-----------|---------|-------|--------|
| List     | Create list | list=[] | N/A | [] |
|          | Set element at index | list[index]=element<br>e.g., Set element at first position | grades=[12,60,15,70,90]<br>grades[0]=55<br>print(grades) | [55,60,15,70,90] |
|          | Slice list | list[1:4]<br>Extract elements between index 1 and 4, excluding index 4 | grades=[12,60,15,70,90]<br>print(grades[1:4]) | [60,15,70] |
|          | Delete slice | list[1:4]=[]<br>Continuously delete data from index 1 to 4, excluding index 4 | grades=[12,60,15,70,90]<br>grades[1:4]=[] | [12,90] |
|          | Concatenate lists | grades=grades+[12,33]<br>Concatenate original list with new list | grades=[12,60,15,70,90]<br>grades=grades+[12,33] | [12,60,15,70,90,12,33] |
|          | List length | length=len(list)<br>Get the length of the list | grades=[12,60,15,70,90]<br>length=len(grades)<br>print(length) | 5 |
|          | Nested list | data=[[3,4,5],[6,7,8]] | data=[[3,4,5],[6,7,8]]<br>print(data) | [[3, 4, 5], [6, 7, 8]] |
|          | Slice assignment | data[0][0:2]=[5,5,5]<br>[0] → First element of the data list<br>[0:2]=[5,5,5] → Sublist from the first to the second element, excluding the third element position (i.e., index 2)<br>[5,5,5] → Assignment | data=[[3,4,5],[6,7,8]]<br>data[0][0:2]=[5,5,5]<br>print(data) | [[5, 5, 5, 5], [6, 7, 8]] |
| Tuple    | Create tuple | Tuple=() | N/A | () |
|          | Indexing | data[0:2] | data=(3,4,5)<br>print(data[0:2]) | (3,4) |
|          | Tuple immutability | data=(3,4,5)<br>data[0]=5<br># Error: Tuple data cannot be changed | data=(3,4,5)<br>data[0]=5<br>print(data) | Error |
