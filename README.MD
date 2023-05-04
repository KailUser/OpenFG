# Welcome to our lib OpenFG
Our small library for python

## How get an api key?

1. [Login into your account](https://kararasenok.ueuo.com/accounts/login.php) (also [registration](https://kararasenok.ueuo.com/accounts/register.php))
2. [Redirect here](https://kararasenok.ueuo.com/api/create/) and create a key
3. Get key and save his
4. Done!

## How use it?
Example code:
````python
import OpenFG
info = Chat("your API key").get_last_message_info("id") # Instead of id, you can specify this: id - message id | sender - sender's name | sender_id - sender's id | message - message | created_at - when sent

if info == "KEY_NOT_FOUND":
    print("Key not found")
else:
    print(info)
````
This code find last message use id of message

Our task list:
- [x] Create our api system
- [x] Create a lib for python
- [ ] Create find user system use his id