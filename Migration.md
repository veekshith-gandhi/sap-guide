## 💡 Part 1: What is XS Classic (XSC)?
- Imagine it’s 2014–2015. SAP HANA is gaining popularity. Now, you want to build apps on top of your SAP HANA database. SAP provides you something called XS Classic (XSC).

## 🧱 What is XS Classic?

1. Think of XSC as a small web server built inside the HANA database.
2. You can write business logic using JavaScript and store it directly in the database.
3. You write files like .xsjs, .xsodata, .hdbtable, etc., and deploy them inside the HANA database.

## 🚫 But what’s the issue?

1. You’re mixing everything together: code, database, web server — all in one place.
2. Not suitable for enterprise-grade scaling (like CI/CD, team collaboration).
3. No concept of containers or microservices.
4. Security concerns, hard to manage users/roles at scale.
5. So eventually… people hit limitations.

