I, Zijing Wang will finish this project on my own.

1. 
After reading file, use readlines to create a list of strings.
Iterate and split() every string
Iterate the list and make it into a list of dictionary using date as keys, and sort them
After keys, which are dates, there are dictionary use e-mail address as keys and followed by user behaviors
For each dictionary, check times of login and login times
Once found a case, total_count += 1
Generate output

2.
After reading file, use readlines to create a list of strings.
Iterate and split() every string
Iterate the list and make it into a list of dictionary using date as keys, and sort them
After keys, which are dates, there are dictionary use e-mail address as keys and followed by user behaviors
check total login times and log out times
Once found a case, total_count += 1
Generate output

3.
After reading file, use readlines to create a list of strings.
Iterate and split() every string
Iterate the list and make it into a list of dictionary using date as keys, and sort them
After keys, which are dates, there are dictionary use e-mail address as keys and followed by user behaviors
check total login times and log out times
Once found a case, total_count += 1
Generate output

4.
Read the whole file
Take all the e-mail address out and form a new list
Split("@") for every string in the list
Take the domain out
Make a dictionary using domains as keys, and count appearing times
Generate output

Errors I came across:
1. When sorting the first dictionary that contains all the data, I could not make it right. I cannot remind the name of the error.
   It end up I have to use two different methods on sorting the big dictionary.
2. When looking for suspicious behaviors, in the beginning, for the new dictionary, I did not initialize the data type, that caused error.
3. When generating output string, because of the complexity of the data type, I kept having errors that prints data that does not make sense.
   I fix it by using isistance(object, datatype)
