# Databas-Labratory

This repo is project of database labratory by farbod fooladi & negin mashayekhi

## **_Disclaimer & WARNINGS:_**

1. **IMPORTANT:** Make sure you **clear all saved Debit/Credit Card or any other
   saved payment info from your Browser** before using the script!
   
2. **Use** this ONLY for **Educational Purposes!** By using this code you agree
   that **I'm not responsible for any kind of trouble** caused by the code.
   
3. **Make sure web-scraping is legal in your region.**

4. This is **NOT a hacking script**, i.e., it can't enroll you for a specific
   course! Instead it finds courses that provide coupon links to make the
   transaction free and then LEGALLY enroll you to the course!

---
## Dependencies
1. python 3.8.5
2. mysql on your computer
3. all libraries imported in code

## Phases
This project have 8 phases

0.  Connecting to Database  
1.  Scraping a site and if there is some changes call Email/SMS API
2.  Login in websites with selenium
3. Kaptcha solver
4. Registration
5. Fill Forms
6. Run some threads for running an script with differents user agents
7. Use Proxies
8. Evade Cloudflare bot detection

## Run
To run the Phase 6,7,8:
first of all you should connect to your mysql account.for this you should replace your username, password, host and the database which is the name of the database of the project in every connection to mysql in all cells of the code.

every phases has 2 main part:
- code: codes of this phase
- database: databases decleration and show tables of this phases

you should run the first cell of the code which is import libraries part.
then you should run the cell of phase0 which make a connection to database
then you should run the phase 6,7,8(for each of them first run the `databases` cells to creating tables then run the `codes` cells)
after that is there a Final part:
first of all run the `Codes` to declare functions of this phases.
then run the `GUI` which open a window at background and you should set parameters as you like to.after you clicked on submit button close that window and go back to the code.
finally run the last cell with name `Run threads` which run 2 thread with the parameters you set just befor.

### GUI Params
1. Time policy (it is the phase 8)
   - random interval
   - fixed interval
   - fixed time
   - **wait until**(suggested)
2. Script
   - **Open Google**(suggested)
   - Login Toplearn
3. User Agent
   - browser
   - browser engine
   - version
   - operating system


