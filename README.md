# Banking System Project

## Overview
A console-based application for managing bank accounts, allowing users to create accounts, deposit/withdraw funds, modify details, transfer money, and view account information.

## Features
- Create, show, modify, and delete accounts
- Deposit and withdraw funds
- Transfer money between accounts
- View all accounts

## Requirements
- C++
- MySQL Connector/C++

## Installation
1. Clone the repository:
2. Set up the MySQL database:
   sql
   CREATE DATABASE class;
   CREATE TABLE accounts (
       acno INT PRIMARY KEY AUTO_INCREMENT,
       name VARCHAR(100),
       deposit DECIMAL(10, 2),
       type CHAR(1),
       password VARCHAR(100)
   );
   create table transactioon(
       transaction_id int AI PK 
       from_account int 
       to_account int 
       amount int 
       transaction_type varchar(50) 
       transaction_time timestam

   );
   
4. Compile and run the application:
   
Contributors
Fikerte Yimer
Fiker Robel
Hawi sebsbie
Haleluya Desalegn
Haset Tesfaye
Fenet Firmosa



   

   
