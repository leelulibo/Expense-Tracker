# WeShare: A Social Expense Tracker

Welcome to WeShare, a web application designed to track expenses shared amongst friends based on social trust.

## Project Overview

WeShare allows users to log in with a valid email address and record their expenses and payment requests. The application simplifies the expense tracking process by focusing on what users spent their money on, when they spent it, and how much they spent.

## User Requirements

### Users
- Each user logs in with a valid email address(student emails). Password or token-based authentication is not required.

### Expenses
- An expense represents any money spent by a user.
- Users can record their expenses, including details such as the amount spent, the date of the expense, and a description.

### Payment Requests
- Users can make payment requests to friends who owe them money.
- When a user pays for expenses on behalf of others, they can record the expense and create payment requests for the owed amounts.
- Payment requests are paid by the recipient, and the amount paid back becomes an expense for the payer.
- The expense of the payer is reduced by the amount paid back.

