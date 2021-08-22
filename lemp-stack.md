# Installing an Nginx server on an AWS ubuntu EC2 instance
Connect to the instance using **EC2 Instance Connect** and run `sudo apt update` .
Install Nginx using `sudo apt install nginx`.
Check the status of your server `sudo systemctl status nginx`
Confirm that you can access your server locally `curl http://localhost:80`
Go to your servers public IP to confirm it is accessible over the Internet, you should see the Nginx welcome page.
![image](https://user-images.githubusercontent.com/43571838/130370713-0727ac0b-b6a6-49b3-8918-6d06466e95b4.png)

# Installing MySQL as your DBMS
Run `sudo apt install mysql-server`. When prompted type 'y' and click Enter.
Run the pre-installed security script to remove insecure default settings and lock down access to your database `mysql_secure_installation`

