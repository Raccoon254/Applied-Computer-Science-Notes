Q- Return the name of a student as well as the age from a group of students.

Using a case statement write a script that can be used with a hotelier who has a -- of 20 fruits, the script should prompt a user to enter 3 or less number of fruits to buy and then return the fruits bought and the amount and the balance to be returned

### Loops in shell scripting

While loops are used for arithmetic operations and it performs statements until a certain condition is met. The syntax is as follows:

```bash
while [ condition ]
do
    command1/ statements
done
```
Example:
```bash
n=1
while [ $n -le 5 ]
do
    echo "Welcome $n times"
    n=$(( n+1 ))
done
```
Write a loop that counts from 15 to 19

```bash
n=15
while [ $n -le 19 ]
do
    echo "$n"
    n=$(( n+1 ))
done
```

Until loop functions the same way as the while loop

```bash
until [ condition ]
do
    command1/ statements
done
```
The for loop is used for non arithmetic operations,

```bash
for a_name in [some names here]
do
    do something for each name
done
```

Example:
```bash
for name in John Jane Mary
do
    echo "Welcome $name"
done
```
Q - use a for loop to read five names and return a name in the position where it was saved ie 1:peter etc

Select loop is also used for arrays like the for loop

```bash
select name in [some names here]
do
    do something for each name
done
```
Example:
```bash
select name in John Jane Mary
do
    echo "Welcome $name"
done
```

Q - use a select loop to read five names and return a name in the position where it was saved ie 1:peter etc

CAT 2
Q- Write a script that will be able to perform the following operations:

use utilities, 2 loops, 2 conditions, 2 net items,

at least 300 lines