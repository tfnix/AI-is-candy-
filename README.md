# AI-is-candy-
_AI is perfect for placeholder data_


<br>


output: <br>
<b>
_Here is the plain-text, space-aligned version of the data:_

</b>

```

              Name  Age                          Email
    Nancy Gonzalez   53   nancy.gonzalez99@example.com
     Jessica Lopez   50    jessica.lopez16@example.com
    Mark Rodriguez   31     mark.rodriguez66@dummy.com
   Patricia Harris   60     patricia.harris59@test.org
    Jessica Wilson   42     jessica.wilson93@dummy.com
Jennifer Rodriguez   32 jennifer.rodriguez70@dummy.com
     James Sanchez   53   james.sanchez50@mockmail.net
     William Brown   41       william.brown77@test.org
       Karen Lewis   48      karen.lewis66@example.com
   William Sanchez   63  william.sanchez44@example.com
      Nancy Thomas   51    nancy.thomas13@mockmail.net
    James Thompson   18     james.thompson25@dummy.com
  Charles Martinez   35 charles.martinez58@example.com
     John Thompson   58    john.thompson82@example.com
     Linda Jackson   18      linda.jackson81@dummy.com
    Joseph Ramirez   31  joseph.ramirez54@mockmail.net
   Michael Johnson   24    michael.johnson62@dummy.com
    Mark Hernandez   57     mark.hernandez86@dummy.com
       James Brown   45      james.brown27@example.com
     William Lewis   45      william.lewis50@dummy.com
      Thomas Jones   20       thomas.jones43@dummy.com
     Thomas Martin   53   thomas.martin72@mockmail.net
   Barbara Sanchez   53  barbara.sanchez1@mockmail.net
    Thomas Jackson   54   thomas.jackson84@example.com
   Matthew Johnson   52 matthew.johnson21@mockmail.net

```
<b>
  
_Now, no formato CSV plain-text_
</b>

```

ID,Name,Age,Email
1,Nancy Gonzalez,53,nancy.gonzalez99@example.com
2,Jessica Lopez,50,jessica.lopez16@example.com
3,Mark Rodriguez,31,mark.rodriguez66@dummy.com
4,Patricia Harris,60,patricia.harris59@test.org
5,Jessica Wilson,42,jessica.wilson93@dummy.com
6,Jennifer Rodriguez,32,jennifer.rodriguez70@dummy.com
7,James Sanchez,53,james.sanchez50@mockmail.net
8,William Brown,41,william.brown77@test.org
9,Karen Lewis,48,karen.lewis66@example.com

....

21,Thomas Jones,20,thomas.jones43@dummy.com
22,Thomas Martin,53,thomas.martin72@mockmail.net
23,Barbara Sanchez,53,barbara.sanchez1@mockmail.net
24,Thomas Jackson,54,thomas.jackson84@example.com
25,Matthew Johnson,52,matthew.johnson21@mockmail.net
```

_A table_ <b>_user_details </b> - _mock(placeholder)-data_
  
</b>

```
ID,Phone,City,Occupation
3,772-555-2629,New York,Accountant
21,358-555-7653,Austin,Analyst
24,599-555-8367,New York,Consultant
14,712-555-1383,Chicago,Writer
8,998-555-9138,Los Angeles,Teacher
22,972-555-3424,Los Angeles,Accountant
16,926-555-1953,Phoenix,Consultant
1,831-555-3507,Seattle,Writer
12,471-555-2618,Los Angeles,Developer

.....

```


_isnt pretty?_ <br>

<br>

<b> _Querying the data - with FK relationship_ </b>
```
$ python3 loader.py

✅ Data successfully loaded into SQLite!

 ID            Name                        Email     City Occupation
  1  Nancy Gonzalez nancy.gonzalez99@example.com  Seattle     Writer
  2   Jessica Lopez  jessica.lopez16@example.com  Seattle   Engineer
  3  Mark Rodriguez   mark.rodriguez66@dummy.com New York Accountant
  4 Patricia Harris   patricia.harris59@test.org  Houston Consultant
  5  Jessica Wilson   jessica.wilson93@dummy.com   Denver Accountant

```


## _Long Live AI!_



