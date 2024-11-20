### REG NUMBER: 212222110045
### NAME: Sowmya V
# CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  
## AIM
To create in Web Application for Test Environment.
## PROBLEM STATEMENT
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
 ### Steps 1:
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2:
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.

## COMMANDS:


### 1. **Install Apache Web Server:**
   ```bash
   sudo yum install httpd -y
   ```

### 2. **Enable Apache to start on boot:**
   ```bash
   sudo systemctl enable httpd
   ```

### 3. **Start the Apache Web Server:**
   ```bash
   sudo systemctl start httpd
   ```

### 4. **Check the Status of Apache:**
   ```bash
   sudo systemctl status httpd
   ```

### 5. **Navigate to the Web Server's Default Directory:**
   ```bash
   cd /var/www/html
   ```

### 6. **Create a PHP/HTML Test File:**
   ```bash
   sudo nano test.php
   ```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```


## OUTPUT

![Screenshot 2024-11-20 195349](https://github.com/user-attachments/assets/f3af4fd2-771a-4d8e-8471-c48087ab0b34)

![Screenshot 2024-11-20 195418](https://github.com/user-attachments/assets/d8a85eb2-8bef-48a3-b20e-60b5ac8ba6eb)

## RESULT
Thus the web application for test environment has successfully been created and executed.

  


