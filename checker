import csv


with open('users.csv')as csvfile:
    datareader = csv.reader(csvfile, delimiter=',')
    for row in datareader:
        print("###################################")
def user_checker():

   valid = True
   while valid == True:
        username = input("Please Enter A username: ")
        if row[0] == username:
            print('username found')
            valid = False 
        else:
            print("username not found ")
def pass_checker():
      valid = True
      while valid == True:
        password = input("Please Enter A password: ")
        if row[1] == password:
            print('password matched')
            print("loggin")
            valid = False
        else:
            print("password not matching")

user_checker()
pass_checker()
