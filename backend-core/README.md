# Backend Core

A Laravel backend API project built as part of my 90-day plan to rebuild strong backend development skills and restart my software development career in Canada.

## Purpose
This project is focused on practicing and demonstrating backend development skills with Laravel, including API design, authentication, database modeling, validation, queues, and testing.

## Tech Stack
- Laravel
- PHP
- MySQL
- Eloquent ORM
- Sanctum
- Vite

## Current Status
Project setup is complete and development is in progress.

## Planned Features
- User authentication
- Projects and tasks management
- CRUD APIs
- Request validation
- Authorization
- Queue jobs
- Automated tests

## Local Setup
```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install
composer run dev
