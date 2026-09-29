# DevPreview Demo Application

A simple web application created to test the DevPreview automated deployment platform.

## Technology

- HTML
- CSS
- JavaScript
- Nginx
- Docker

## Purpose

This repository is used as the controlled demo application for testing:

GitHub → Jenkins → Docker → Ansible → Browser Preview

## Run with Docker

Build the image:

```bash
docker build -t devpreview-demo .
