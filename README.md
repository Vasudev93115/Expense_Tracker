# 💰 Daily Expense Tracker (PHP + MySQL)

A simple web-based application to record and manage your daily expenses.  
Built with **PHP**, **MySQL**, HTML, CSS, and Bootstrap.

---

## 📌 Features
- User registration & login
- Add, edit, and delete expenses
- View expense history by date
- Summary of total spending
- Simple, responsive design

---

## 🛠 Requirements
- [XAMPP](https://www.apachefriends.org/) or [Laragon](https://laragon.org/) (or any PHP + MySQL server)
- PHP 7.4+ (or compatible version)
- MySQL / MariaDB

---

## 🚀 Setup Instructions

### 1. Clone or Download the Project
```bash
git clone https://github.com/your-username/daily-expense-tracker.git
```
Or download as ZIP and extract.

---

### 2. Move to Server Folder
- **XAMPP**: move the project folder into  
  ```
  C:\xampp\htdocs\
  ```
- **Laragon**: move the project folder into  
  ```
  C:\laragon\www\
  ```

---

### 3. Create the Database
1. Start **Apache** and **MySQL** in your server control panel.
2. Open **phpMyAdmin** in browser:
   ```
   http://localhost/phpmyadmin
   ```
3. Create a new database:
   ```
   expenditure
   ```

---

### 4. Import the SQL File
1. In phpMyAdmin, select the `expenditure` database.
2. Go to the **Import** tab.
3. Choose the file:
   ```
   expenditure.sql
   ```
4. Click **Go** to import.

---

### 5. Configure Database Connection
- Open the project folder → find the database config file (e.g. `config.php` or `db.php`).
- Update the database details:
```php
$servername = "localhost";
$username   = "root";
$password   = ""; // usually empty for local server
$dbname     = "expenditure";
```

---

### 6. Run the Project
- Open in browser:
  ```
  http://localhost/daily-expense-tracker
  ```
  *(If using Laragon: `http://daily-expense-tracker.test`)*

---

✨Screenshots :

   1) Front-Page : 
  
      ![front](https://user-images.githubusercontent.com/126175004/235640182-c909c2a9-1b71-44cd-a729-107224bb6eec.png)
      
   2) Login-Page :
  
      ![login](https://user-images.githubusercontent.com/126175004/235640335-01862545-a837-44b3-bf95-e33ab3ab81c7.png)
      
   3) Signup-Page :
  
      ![signup](https://user-images.githubusercontent.com/126175004/235640501-a0896935-f8d6-4e94-a323-52b21b5d2ad2.png)
      
   4) User-Dashboard :
      
      ![Screenshot 2023-05-02 153308](https://user-images.githubusercontent.com/126175004/235640702-1f570137-11a8-4f2e-bca2-52c966440edd.png)
      
   5) Add-Expenses :

      ![add-expense](https://user-images.githubusercontent.com/126175004/235640826-f858f739-0551-4a0f-8d78-1f0bc0354185.png)
      
   6) Manage-Expense :
   
      ![manage-expense](https://user-images.githubusercontent.com/126175004/235641022-95933116-7fc0-4d0a-b987-ba36bbb88a2f.png)
      
   7) Add-Lending :
  
      ![add-lending](https://user-images.githubusercontent.com/126175004/235641132-644eb6f8-5cf9-49b1-8d3e-612df3829a16.png)
      
   8) Manage-Lending :
      
      ![manage-lending](https://user-images.githubusercontent.com/126175004/235641243-2ed2b7c0-1204-4208-bd5a-57220003c6f9.png)
      
   9) Analytics :
     
      ![analytics](https://user-images.githubusercontent.com/126175004/235641350-d98be171-00c2-4572-b723-10ad3a206065.png)
      
   10) Report : 
   
       ![report](https://user-images.githubusercontent.com/126175004/235641482-20b0ef0a-4d79-4092-b64d-e1e2ad9b1b7d.png)
       
       ![Screenshot 2023-05-02 155222](https://user-images.githubusercontent.com/126175004/235642061-6ddb28ef-7019-4bf9-85c9-216988e5610e.png)
       
   11) Setting : 
       
       ![user_profile](https://user-images.githubusercontent.com/126175004/235642200-d75ec57e-6ad5-44e5-93a5-994ee0e95eaa.png)

## Contributing

You're all welcome to contribute to this project! Whether it's fixing bugs, improving existing features, or suggesting new ideas—every bit helps. Feel free to fork the repo, open issues, or submit pull requests.

Let's make this project better together!
       

          



      

      
      
      


      

      

      
   
    




 
 



  
    
    







