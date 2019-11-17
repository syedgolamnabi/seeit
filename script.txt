
file_name = ""

while file_name != "exit.txt":
        file_name = input("Write down file Name: ")+".txt"
        try:
            print('\n')
            print(open(file_name).read())
            print('\n')

        except:
            print('\n')
            print("No such file in directory")
            print('\n')

print("Exiting Script")
