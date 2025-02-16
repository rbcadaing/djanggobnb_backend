# Djangobnb - Fullstack Airbnb clone - Next.js 14 / React, Tailwind, Django, Django Rest Framework

This repository is for the frontend part of my video tutorial series. You can find it here:
[YOUTUBE PLAYLIST](https://www.youtube.com/playlist?list=PLpyspNLjzwBnP-906FBRP5qzB4YXjMvnT)

## Things you will learn and implement

- Next.js 14
- React
- Tailwind
- Django
- Django rest framework
- Docker compose
- Postgresql
- Deployment to Digital Ocean

## Features in this project

- Fully responsive design built with Tailwind
- Authentication using Django Allauth (Email log in)
- How to use react-date-range and other packages
- How to upload images using fetch
- Live chat using web sockets

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.


## Install Virtual Environment
1. python3 -m venv env
2. /env/Scripts/activate
3. pip3 install django
4. django-admin startproject djangobnbbe .
5. update the database by running migrations
    a. docker compose exec web python manage.py makemigrations
    b. docker compose exec web python manage.py migrate
6. docker compose exec web python manage.py startapp useraccount
7. docker compose exec web python manage.py startapp property
8. Create Super user "docker compose exec -it web python manage.py createsuperuser"


## Docker Issues
1. entrypoint.sh not found https://stackoverflow.com/questions/38905135/why-wont-my-docker-entrypoint-sh-execute

