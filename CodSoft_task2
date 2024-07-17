import random
import string

def main():
    # Define the possible characters for the password
    charset = string.ascii_letters + string.digits + "!@#$%^&*()"
    
    # Prompt the user to specify the desired length of the password
    length = int(input("Enter the desired length of the password: "))
    
    # Generate the password
    password = ''.join(random.choice(charset) for _ in range(length))
    
    # Display the password
    print(f"Generated Password: {password}")

if _name_ == "_main_":
    main()
