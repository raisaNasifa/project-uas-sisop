# Docker Web Application

Aplikasi web sederhana berbasis HTML yang dijalankan menggunakan Docker.

Build:
docker build -t docker-web .

Run:
docker run -d -p 8080:80 docker-web

Akses aplikasi melalui browser:
http://localhost:8080
