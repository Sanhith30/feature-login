# login.py

def login(username, password):
    if username == "admin" and password == "password":
        return "Login successful!"
    else:
        return "Invalid credentials"
