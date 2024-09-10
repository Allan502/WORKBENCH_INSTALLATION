# 🚀 Commands used to install MySQL-Server

## 1. Install MySQL-Server

🔄 **Update package list:**

```bash
sudo apt update
```

🔧 **Install MySQL server:**
```bash
sudo apt install mysql-server -y
```

🔍 **Check MySQL status:**
```bash
systemctl status mysql
```

🔑 **Access the MySQL console:**
```bash
sudo su
mysql -u root -p
```
Enter password: 1234

🔐 **Set up root with a specific password:**
```sql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '1234';
```

📂 **Show available databases:**
```sql
show databases;
```

## 2. Install MySQL-Workbench-Community

🔧 **Install the package `dpkg`:**
```bash
sudo apt install dpkg
```

📦 **Install MySQL APT configuration:**
```bash
sudo dpkg -i mysql-apt-config_0.8.25-1_all.deb
```

🔄 **If necessary, reconfigure MySQL APT:**
```bash
sudo dpkg-reconfigure mysql-apt-config
```

🔄 **Update package list:**
```bash
sudo apt update
```

🔝 **Update system packages:**
```bash
sudo apt upgrade
```

🔧 **Install MySQL Workbench Community:**
```bash
sudo apt install mysql-workbench-community
# or
sudo snap install mysql-workbench-community
```

## 🚀 IMPORTANTS COMMANDS 

1. **View the status of the MySQL service**:
    
    ```bash
    sudo systemctl status mysql
    ```
    
2. **Start the MySQL service**:
    
    ```bash
    sudo systemctl start mysql
    ```
    
3. **Stop the MySQL service**:
    
    ```bash
    sudo systemctl stop mysql
    ```
    
4. **Restart the MySQL service**:
    
    ```bash
    sudo systemctl restart mysql
    ```
