# Earn App — Full Starter

## Included
- Modern login/register page
- Customer earning dashboard
- Tasks + daily task
- Persistent SQLite database
- Transaction history
- Referral code/link
- Withdrawal request workflow
- Admin panel
- User list and balances
- Withdrawal approve/reject
- Rejected withdrawal returned to user balance

## Run
1. Install Node.js LTS.
2. Extract this ZIP.
3. Run `npm install`.
4. Copy `.env.example` to `.env`.
5. Change ADMIN_EMAIL and ADMIN_PASSWORD.
6. Run `npm start`.
7. Customer: http://localhost:3000
8. Admin: http://localhost:3000/admin.html

## Production
Before accepting real money, use HTTPS, a production database, strong password hashing (Argon2/bcrypt), secure sessions, rate limiting, audit logs, backups, KYC/AML as applicable, and a payment provider using your own verified merchant account. The admin approval in this starter does not itself transfer money.
