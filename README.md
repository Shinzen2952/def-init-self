# def-init-self
class Account:
    def __init__(self,email,nickname,password):
        self.email = input_email
        self.nickname = input_nickname
        self.password = input_password

        print(f"your email is: {email}")
        print(f"your nickname is: {nickname}")
        print(f"your password is encrypted as: {password} ")
        

input_email = input("Enter your email here: ").lower()
input_nickname = input("Enter your nickname here: ").lower()
#encryption
input_password = input("enter your password : ").lower()
password_value = input_password.replace("a","9010")
input_password = password_value[::-1]

p = Account(input_email,input_nickname,input_password)
