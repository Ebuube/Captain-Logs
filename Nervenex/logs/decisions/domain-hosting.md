# Decision Log: Domain hosting

## 📝 Context
- Heroku's subdomain name is very random and does not reflect what we do at Nervenex.

## 📊 Options Considered
1. `.tech` domaain
2. `.live` domain

## ✅ Final Decision
- We are choosing `.live` domain. The `.tech` domain we have expires on April 11, 2025, while the `.live` domain expires in a year time.

## 🚀 Implementation Steps
1. Login in to Name.com
2. Link GitHub Student Developer (GSD) account to Name.com
3. Request `miestudio.live` domain and use credit from GSD account.
4. Create **ANAME** records for `nervenex` and `api.nervenex` subdomains.
5. Connect these domains to the heroku apps: Nervenex and Nervenex-api.
6. Update the config variables for these apps.
7. Update the installation doc on Google Drive.
8. Log the change.
