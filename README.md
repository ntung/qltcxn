# Introduction: Shelter House Financial Management System
<p>This initiative aims to support House Managers in shelter homes by providing robust tools for managing revenues and expenditures.</p>

<p>The core challenge lies in the financial timeline misalignment: residents receive public housing funds fortnightly, while house operations and expense tracking are handled weekly. This critical timing difference consistently results in discrepancies and mismatches between funds received and funds spent.</p>

<p>To resolve this, we are developing a bespoke, web-based application. This solution will empower House Managers to accurately and efficiently track all financial activities in a way that is tailored specifically to their operational and funding cycles.</p>

# Project structure
The web-based application is built with server client architecture.
## Server
* Core REST API: Python FastAPI, Pydantic, MongoDB
* Templates: default views to add, update, remove all items.
## Client
* Tech: Vue.js, Nuxt, SCSS
* Built with Vite

# Manual
Some screenshots of the application are provided.
## Landing page - Home page
![Landing page](/manual/img/01_homepage.png)
## List of Tenants/Residents
![Tenants](/manual/img/02_tenants.png)
## List of Rents
![Rents](/manual/img/03_rents.png)
## List of Incomes (i.e., Payments from Housing Benefits)
![Rents](/manual/img/04_incomes.png)
## Reports for Rents and Payments
Chose a tenant, then select the report period by selecting `From Week/Date` and `To Week/Date`, then hit 
`Search` button.
![Rents](/manual/img/05_report_rents_payments.png)
