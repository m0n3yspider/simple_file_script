#David Johnson 5-17-2020 Assignment 10.1

import os

#main function
def main():
    #prompt for input from user
    directory = input("Enter the directory that you want to save the file: ")
    filename = input("Enter the filename: ")
    name = input("Enter your name: ")
    address = input("Enter your address: ")
    phone_number = input("Enter your phone number: ")

    #determine if directory exists
    if os.path.isdir(directory):
        with open(os.path.join(directory, filename), 'w') as write_file:
            write_file.write(name + ',' + address + ',' + phone_number + '\n')
        
        #printing file contents
        with open(os.path.join(directory, filename), 'r') as read_file:
            print('File contents: ', read_file.read())

    else:
        print("The directory does not exist.")

main()

