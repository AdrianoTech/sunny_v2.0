# Sunny.py

Sunny.py (now at v.2.0) is a program (written in python) that in only 0.23 seconds (on a lapton running AMD Ryzen5 35000U CPU with Radeon Vega Mobile Gfx) is able to convert the data produced by Ussing Chamber software "Clamp" (devoleped by Dipl. Ing K. Mussler, Aachen), from .cla in ordered .xlsx tables.

It has many advantages:
- each column starts with the corresponding title. Files can be therefore immediately imported into R
- intervals are specified in the Excel file
- Max and min for each interval are automatically recognized by the program, which plot also their difference
- it gives you the possibility to edit and save the graphs by just clicking the whithe box "Graph?"

## Libraries needed
Before to start you need to have installed the following python libraries: \
matplotlib.pyplot \
xlsxwriter \
datetime \
tkinter \
os 

to instal them you can easily execute "pip install" in cmd.  \
I.e.: 

```console
user@bar:~$ pip install xlsxwriter
```

## Improvements from v.1
In this version the following updates have been done:
- a graphic user interface has been added to make the program easier to use
- a bug in convert() function has been corrected 

## Test the Program
There have been given two files to you, to test the program:
- a .cla file (that can be converted with sunny.py into a .xlsx table)
- an .xlsx table obtained by converting a .cla file with sunny


by question please write me at: Adriano.Sanna@anatomie.med.uni-giessen.de

