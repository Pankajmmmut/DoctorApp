# DoctorApp
![ToDoApp Logo]([https://tse3.mm.bing.net/th?id=OIP.L0sEsLlqKCTvAyMBHoARSgHaDp&pid=Api&P=0&h=180](https://www.scnsoft.com/blog-pictures/healthcare/doctor_apps-01_1.png)) 

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Model](#model)
- [Contributing](#contributing)


## Introduction

DoctorApp is a web-based application designed to manage Hospital manage tasks. It provides functionalities of add delte update and read information about Doctor patients and admin.

## Features

- View a list of all doctor and patients.
- View details of a specific doctor and patient by its ID.
- Create a new doctor by admin.
- Update an existing doctor and patients details.
- Delete a doctor or patients from the system.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database


## Model

The `Doctor` model represents a doctor with the following attributes:

- `id` (Long): Unique identifier for the doctor.
- `doctorName` (String): Name or description of the doctor.
- `department` (String): Name of department of doctor.
- etc.

  The `Patient` model represents a patient with the following attributes:

- `id` (Long): Unique identifier for the patient.
- `patientName` (String): Name or description of the patient.
- `age` (String): Name of department of patient.
- etc.

## API Documentation

API documentation is generated automatically using SpringDoc and can be accessed at `http://localhost:8080/swagger-ui.html` (when the application is running). It provides detailed information about the available REST endpoints, request parameters, and responses.

## Contributing

We welcome contributions to improve the Doctor. If you find any issues or want to add new features, please create a pull request, and we will review it together.
