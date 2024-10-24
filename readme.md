# E-Learning Platform Made with Laravel
onGoing

# Installation
1. Clone this repo
```
git clone https://github.com/JonathanZefanya/E-LAB-IF.git
```

2. Install composer packages
```
cd E-LAB-IF
```
```
composer install
```

3. Create and setup .env file
```
cp .env.example .env
```
```
php artisan key:generate
```

6. Migrate and insert records
```
php artisan migrate --seed
```