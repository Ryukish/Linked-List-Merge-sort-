# Linked-List-Merge-sort


* Read into linked list
* Do commands
* Output to file

One record per Line (end with \n)
```
{id:1234567,first:Mary,last:Green,DOB:1996-10-03,GPA:4.0}
{id:1234568,first:Peter,last:White,DOB:1997-05-22,GPA:3.8}
{id:1654238,first:Nick,last:Park,DOB:1995-08-18,GPA:4.0}
{id:1234587,first:Katy,last:Green,DOB:1995-08-18,GPA:4.0}
```
```
struct student{
int id;
string first;
string last;
string DOB
double gpa;
}
```
### General rules
* use 'while (getline, str)' to grab each line to the end of file
* same ID = duplicated record
* update with the latter one (update with the later one)
* if somebody's name has more than one word, the separator would be underline "_"
* No empty values will be given in the columns
* no other character or space will be given(no need for me to check)

## Types of Sorts

* ID
* FIRST name
* LAST name
* DOB (yyyy-mm-dd)
* GPA (double)
* (all case sensitive)

If two or more records by passing all commands have same order, the one
with lower id value should be outputted first.

## Output to File
Output should be based on the sequence of commands commands top -> bottom output line end with \n

