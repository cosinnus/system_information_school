## System Information School
School information system is a useful website to facilitate school data collection. Built with laravel v.7.0, vue.js v.2.5.17, vue router v.3.3.4 and vuex v.3.4.0
### Before installation
- Please configuration database for this projects. Change in .env.example to .env
- Move file image in folder public/image to folder storage/app/public/image
- php v.7 or later
### Installation

```
composer install
php artisan application:install
```
If you want development you can keyword in cli
```
npm install
```
### Start Serve
```
php artisan serve
```
### Middleware
- Administrator
- Admin
- Teacher
### Feature
- Admin Template
- Dashboards
- Passport API authentication
- CRUD school
- CRUD class
- CRUD study
- CRUD teacher
- CRUD student
- CRUD homeroom teacher
- CRUD task assessment
- CRUD report card
- Export excel in all tables
- Import excel in all tables
- Notes
### The npm package used
- axios
- jquery
- chart.js
- laravel-vue-pagination
- metismenu
- sweetalert2
### Package composer used
- laravel/passport
- maatwebsite/excel
### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
