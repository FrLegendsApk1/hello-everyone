# hello-everyone
https://frlegendsapk.org/
# Simple tool to greet users with their name and father's name

def greet_user():
    print("Welcome to the greeting tool!")
    
    # Get user input for the name and father's name
    user_name = input("Enter your name: ")
    father_name = input("Enter your father's name: ")
    
    # Print the greeting message
    print(f"Hello {user_name}, son/daughter of {father_name}!")

if __name__ == "__main__":
    greet_user()
