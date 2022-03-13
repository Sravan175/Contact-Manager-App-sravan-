# Contact-Manager-App-sravan-
##!/usr/bin/evn python3

#

# Contact Manager Program

#

import csv

FILENAME = "contacts.csv"

def view_contacts (contacts): number int(input("Number: ")) if number <1 or number> len (conta

print("invalid number")

else:

contact contacts [number-1]

print("Name: " + contact[0];

print(" 1:^ prime prime + contact[1] print("Phone: " + contact [2]

print()

def add_contacts (contacts):

name=input("Name: ")

email input("Email: ") phone input("Phone: ")

contact = lceil rceil

contact.append(name)

contact.append(email).

contact.append(phone)

contacts.append(contact) write_contacts (contacts)

print (name + " was added")

print()

def delete_contacts (contacts):

number = int(input("Number: "))

if number <0 or number > len (conta

print("invalid number") else:

contact contacts.pop(numbe

write_contacts (contacts) print(contact [0] + " was del

return contacts.

def

display_menu():

print("Contact Manager") print()

print("COMMAND MENU")

print("list Display all contacts",

"\nadd Add a contact", "\nde "\nexit Exit program")

print()

def main():

display_menu()

contacts = read_contacts() while True:

command=input("Command: ")

if command.lower ()=="1ist"; list contacts (contacts)

elif command.lower() == "view":

view_contacts (contacts) elif command.lower() == " dd^ prime prime :

add_contacts (contacts)

elif command.lower f()==^ prime prime del"

delete_contacts (contacts)

elif command. lower() == "exit":

print("Good bye!")

break

else:

print("Invalid command. Plea

if_name__

== "__main__":

main()
