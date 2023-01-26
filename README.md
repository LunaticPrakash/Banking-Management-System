# Banking-Management-System
I've tried to implement banking system to some extent using Python3. It's only works in cmd/terminal mode. Just made this as a warm-up project for practicing Python and MySQL.

## Requirements :- 
- Python3
- Twilio
- MySQL
- (Optional) Internet connection (either slow or fast) - It is used only for sending sms to customer mobile number.

 ### Other Python Modules : -
 - Tabulate
 - Playsound
 
## How to install Requirements :-

1. **Python3** can be installed from their official site https://www.python.org/ . Or you can use anaconda environment.

2. **Twilio** can be installed using PIP :- 
```
pip3 install twilio
```

3.  You can install **MySQL** by following the procedure mentioned in official documentation on : - 
- For Linux : https://dev.mysql.com/doc/refman/8.0/en/linux-installation.html
- For WIndows : https://dev.mysql.com/doc/refman/8.0/en/windows-installation.html

Yeah, you should refer to youtube or stackoverflow for its installation XD.

4. **Playsound** can be installed using PIP :-
```
pip3 install playsound
```

## Description & Features :-

- This project includes implementation of some of common task of Banking-System. 
- SMS Banking also available. You'll be notified every time any transaction(deposit/withdraw) or update in any of your existing data is made.
- Currency counting sound and error sound are also available.

## Getting Started :-
- Admin credentials (You can change it in program) <br>
  **admin_id = 0000** <br>
  **admin_passwd = 'root'**
  
- Start your MySQL server :
  For windows -> ``` C:\> "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" ``` <br>
  For Linux -> ``` sudo systemctl start mysql ```
  
- (Optional) You can check your MySQL server : <br>
  For windows - ``` "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqlshow" -u root mysql ``` <br>
  For Linux - ``` "sudo mysql -u <username> -p" ```  <br>
  It might ask you for password, then enter your MySQL password. Replace < username > with your MySQL username.
  
- Go login at <a href="https://www.twilio.com/console">Twilio Console </a> and set up your account and get your credentials(ACCOUNT_SID, AUTH_TOKEN) and a phone     number for sending sms. For more info you can look at :- <a href= "https://www.twilio.com/docs/sms/quickstart/python" >Twilio Python SMS </a> <br>
 
  Once you get your credentials and twilio mobile number place it in code at proper place(shown in below screenshot)
  
   <img src="https://user-images.githubusercontent.com/56812557/214742546-0dad4975-fc62-4a9a-98d8-9569150726d3.png" alt="twilio-token-ss" width="30%" height="40%" > <br> 
   <img src="https://user-images.githubusercontent.com/56812557/214742544-7aeb7b4a-32f5-40fd-9216-68e5ec458cc3.png" alt="twilio-mobile-ss" width="40%" height="40%" >  
  
 - Run the file by typing following command :-
 ```
 python3 Banking-Management-System.py
 ```
 
 - Intially after program runs, it will ask you for hostname, username, password, database name. <br>
   Enter **hostname = localhost** and **database name = bank_db** <br>
   Enter username and password according to your own MySQL credentials <br>
 Then just go with the flow...
  

## Output :- 
   
   1. Login Panel - This is the first screen you'll see.
   <img src="https://user-images.githubusercontent.com/56812557/214742549-cb5efe24-ded7-4d4e-9bd8-e3d983a33f37.png" alt="Output-1" width="50%" height="50%" >
   
   2. After admin login :
   <img src="https://user-images.githubusercontent.com/56812557/214742554-11d9eb77-0833-417a-a382-590fc98f31e4.png" alt="Output-2" width="40%" height="22%" >
   
   3. After customer login :
   <img src="https://user-images.githubusercontent.com/56812557/214742558-a7eae094-02d2-423a-aae6-f640a493bbee.png" alt="Output-3" width="40%" height="13%" >
   
   4. Transaction Menu - When customer selects Transaction and Deposit Money :
   <img src="https://user-images.githubusercontent.com/56812557/214742570-0501d312-aae2-4817-a193-21be2864c6a9.png" alt="Output-4" width="40%" height="40%" >
   
   5. Transaction Menu - When customer selects Transaction and Withdraw Money :
   <img src="https://user-images.githubusercontent.com/56812557/214742575-c93eaf24-f3f1-47b8-a417-f7af9ea83b8f.png" alt="Output-5" width="40%" height="40%" >
   
   6. When admin opens all customer details :
   <img src="https://user-images.githubusercontent.com/56812557/214742578-d7041662-8cff-4a6a-afe8-df5544d0c366.png" alt="Output-6" width="80%" height="90%" >
   
   7. When admin opens all transaction details :
   <img src="https://user-images.githubusercontent.com/56812557/214742540-edae24ab-289f-4f32-a1dd-d104aa5dc1ac.png" alt="Output-7" width="50%" height="40%" >

   8. SMS-Banking messages :
   <img src="https://user-images.githubusercontent.com/56812557/214742543-3ace447a-e6e0-4261-b262-d8fa548261d0.png" alt="Output-8" width="20%" height="20%" >

## Dev :- Prakash Gupta
