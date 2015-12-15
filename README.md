# Practice 2014 - 09: Tools of the Trade

## Background
King Theoden has responded to the raids upon his lands and the threat of Saruman
by withdrawing his people into Helm’s Deep. Here they hope to make their stand
against the forces of evil, but they’ve run into a problem! The armory doesn’t
have enough weapons of each type to arm everyone with the weapon with which they
are most proficient. Instead, the quartermaster must figure out how to
distribute the weapons they do have so that their combat ability is maximized,
and so that they can repulse the Uruk-hai armies.

## Description

### Input
The first line of the input is an integer giving the number of test cases. Each
test case begins with a line of the form ”N M”, where N is the number of weapon
types and M is the number of soldiers. N lines follow, each of the form C T,
where C is the character representing the weapon, and T is the number of that
weapon available. M lines follow that, describing the proficiencies of each
soldier (in decreasing order) in terms of the character representation of
the weapons.

### Output
For each test case, give an integer on its own line as output. This number is
the total inexperience for the best (minimal) assignment of weapons. This is
measured as the total of the number of steps from their favored weapon that each
soldier is assigned; for example, a soldier with the preferences ABCD assigned
weapon C would increase the total inexperience by 2, whereas if assigned B he
would increase the total inexperience by 1.

## Sample
### Input
```
2
4 6
A 1
B 2
C 3
D 4
ABCD
BDCA
BDCA
BACD
CDBA
ABCD
4 3
E 1
F 1
B 1
A 1
ABEF
ABEF
ABEF
```

### Output
```
3
3
```
