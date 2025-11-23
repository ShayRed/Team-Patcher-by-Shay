# 🧩 Apache Installation on FreeBSD

This guide explains how to install and configure Apache 2.4 on FreeBSD

---

## 🧭 Step 1: Install Apache using the FreeBSD package manager

pkg install apache24



## 🚀 Step 2: Enable Apache at system startup


sysrc apache24_enable=YES



## ▶️ Step 3: Start Apache


service apache24 start


## Check the status:

service apache24 status



Important: The path on FreeBSD is always located here. In the data directory, you will place all folders and files used by the patcher 

## Web Directory	/usr/local/www/apache24/data