# mini-crm

Laravel Documentation : https://laravel.com/docs

Adminpanel to manage companies

Basically, project to manage companies and their employees. Mini-CRM.

1. - [x]     Basic Laravel Auth: ability to log in as administrator
1. - [x]     Use database seeds to create first user with email admin@admin.com and password “password”
1. - [x]     CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
1. - [x]     Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website
1. - [x]     Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
1. - [x]     Use database migrations to create those schemas above
1. - [x]     Store companies logos in storage/app/public folder and make them accessible from public
1. - [x]     Use basic Laravel resource controllers with default methods – index, create, store etc.
1. - [x]     Use Laravel’s validation function, using Request classes
1. - [x]     Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
1. - [x]     Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register

Optional Feature

- Use Swal JS for confirmation
- Use Data Table
- Use Permission to multi user
