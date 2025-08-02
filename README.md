# Dog class and Dog test read me
# Author: Hans Telford
# Date: 01-Dec-2022
# Updated: 02-Aug-2025
Data:
string name (owner's name for the dog)
string type (e.g. Bulldog, Collie, Fox Terrier)
string sex (e.g. Male, Female)
bool isDesexed (e.g. true or false)
DateTime birthDate (birth details of the dog) --- not included in source code provided
DateTime firstVisit (date details of first visit to vet)  --- not included in source code provided
string owner (owners full name)  --- not included in source code provided
string ownerPhone (owners mobile phone number)  --- not included in source code provided
string ownerEmail (owners email address)  --- not included in source code provided

Methods:
Default Constructor - public Dog ()
Parameterised Constructor - public Dog (9 input values)
Get and Set methods for each data field
Override ToString() method - customised for class
Implemented CompareTo() method for alphabetically sorting Dog instances by name (required when using List<Dog>.Sort() method
