
# Angular 18 Project Setup

Follow the steps below to get everything set up and running locally.

---

## 🚀 Getting Started

### 1. 📂 Navigate to the Frontend Project Directory

Open a terminal and navigate to the directory of your **frontend** project:

```bash
cd path/to/Frontend/Frontend
```

### 2. 📥 Install Dependencies

To install all required dependencies for your Angular project, run the following command:

```bash
npm install
```

This command will install the necessary node packages for your project.

### 3. 🚀 Start the Angular Development Server

Once dependencies are installed, you can start the Angular development server by running:

```bash
ng serve
```

Your Angular application will be available at [http://localhost:4200/](http://localhost:4200/). Open this URL in your browser to see your app in action.

---

## ⚙️ Backend Setup

### 4. 🗂 Run SQL Scripts

To set up your database, run the SQL scripts provided in your preferred SQL management tool. **SQL Server 2022** is the preferred version for compatibility:

- **Recommended SQL Version**: SQL Server 2022
- Execute the provided SQL scripts to set up the database schema and data.

### 5. 🔧 Modify the Connection String

In your **C#** backend application, you need to modify the `appsettings.json` file to match your database credentials. Update the connection string as shown below:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=your-server;Database=your-database;User Id=your-username;Password=your-password;"
  }
}
```

Make sure the connection string reflects the actual database server and credentials you're using.

---


## 📋 Summary of Steps

1. 📂 Navigate to your **frontend** project directory.
2. 📥 Install dependencies using `npm install`.
3. 🚀 Start the development server with `ng serve`.
4. 🗂 Run the **SQL** scripts in **SQL Server 2022**.
5. 🔧 Update the **connection string** in `appsettings.json` to match your database credentials

**Happy Coding!** 🎉
