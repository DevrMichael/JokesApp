# Joke Generator App

## Overview

The Joke Generator App is a .NET-based web application developed using Visual Studio on macOS. It serves as an interactive platform for users to explore and enjoy a wide range of jokes. With built-in authorization features, the app ensures a personalized experience while maintaining user security. Jokes and their answers are stored in a robust database, allowing for efficient retrieval and management.

## Features

- **User Authentication:** Secure signup and login functionality.
- **Joke Browsing:** Users can browse through a curated list of jokes.
- **Favorites:** Users can mark jokes as favorites and access them easily.
- **Contribution:** Registered users can submit new jokes for approval.
- **Responsive Design:** Optimized for both desktop and mobile use.

## Technologies Used

- **.NET 5.0:** For building the application.
- **ASP.NET Core:** For creating the web application and services.
- **Entity Framework Core:** For database access.
- **SQL Server:** As the database backend (alternatively, describe the database you used).
- **Bootstrap:** For frontend design.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [.NET 5.0 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio for Mac](https://visualstudio.microsoft.com/vs/mac/)
- SQL Server (or any other database you used, with installation links)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/joke-generator-app.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd joke-generator-app
   ```
3. **Install dependencies**
   ```bash
   dotnet restore
   ```
4. **Set up the database**

Ensure your database server is running.

Update the connection string in appsettings.json to point to your database.

Apply migrations to create the database schema:

   ```bash
   dotnet ef database update
   ```
5. **Run the application**
   ```bash
   dotnet run
   ```
## Usage
After launching the app, you can:

- Register a new user account.
- Browse through the collection of jokes.
- Submit new jokes for inclusion in the database (subject to approval).

  
