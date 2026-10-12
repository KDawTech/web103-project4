# WEB103 Unit 4 Lab: UnEarthed, Part 4

## Overview

UnEarthed is a full-stack gift discovery app built with React, Express, and PostgreSQL. This Unit 4 version adds complete CRUD functionality so users can create, view, edit, and delete gifts through the frontend while changes are persisted in the database.

## Features

- View all gifts from PostgreSQL on the homepage
- View a unique details page for each gift
- Create a new gift from the **+ Add Gift** form
- Edit an existing gift from the three-dot menu on each card
- Delete an existing gift from the edit page
- Persist create, update, and delete operations through the Express API
- Display gift information including name, price point, audience, image, description, submitter, and submitted date

## Tech Stack

- React
- Vite
- React Router
- Node.js
- Express
- PostgreSQL
- pg
- Nodemon
- dotenv
- CORS

## Project Structure

```text
client/   React + Vite frontend
server/   Express + PostgreSQL backend
