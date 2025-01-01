# Python
def login(username, password):
    if username == "vk" and password == "22018886":
        return True
    else:
        return False

user_input_username = input("Enter your username: ")
user_input_password = input("Enter your password: ")

if login(user_input_username, user_input_password):
    print("Login successful !")
else:
    print('Login failed')
