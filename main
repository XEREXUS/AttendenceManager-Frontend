import streamlit as st

def validate_login(username, password):
  # Simulate a login validation mechanism (replace with your actual authentication logic)
  # In a real application, you would likely store usernames and hashed passwords in a database
  # and compare the entered password with the hashed version stored for the username
  if username == "user" and password == "password":
    return True
  else:
    return False

st.title("Login Page")

username = st.text_input("Username")
password = st.text_input("Password", type="password")  # Mask password input

if st.button("Login"):
  if validate_login(username, password):
    st.success("Login successful!")
    # Replace with your application's main content after successful login
    st.write("Welcome to the application!")
  else:
    st.error("Invalid username or password")
