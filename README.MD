<h1 align="center">
  <br />
  <img
    src="./_docs/assets/icon.png"
    alt="Mega Man Robots API"
    width="150"
  />
  <br />
  <b>Mega Man Robots API</b>
  <br />
  <sub><sup><b>(MEGA-MAN-ROBOTS)</b></sup></sub>
  <br />
  <div>
    <a href="https://github.com/amandatainan/MegaApiDotnetCore/actions/workflows/build.yml">
      <img
        src="https://github.com/amandatainan/MegaApiDotnetCore/actions/workflows/build.yml/badge.svg"
        alt="Build Status"
      />
    </a>
    <a href="https://github.com/amandatainan/MegaApiDotnetCore/releases/latest">
      <img
        src="https://img.shields.io/github/v/release/amandatainan/MegaApiDotnetCore"
        alt="Latest Release"
      />
    </a>
  </div>
</h1>

<p align="center">
  Mega Man Robots API is a .NET Core-based backend service designed to provide JSON-formatted data on the bosses and robots from the Mega Man video game series.
</p>

<p align="center">
  Built with .NET Core 3.1, Entity Framework Core, and other modern web development technologies, this API offers a seamless way to interact with Mega Man robot data in a RESTful manner.
</p>

<p align="center">
  <img src="./_docs/assets/carbon.png" alt="API Overview" />
</p>

---

## 🚀 Features

- **List of all Robots**: Retrieve all robot data from the Mega Man universe.
- **Robot Details**: Get detailed information about a specific robot, including name, abilities, and more.
- **Create Robot**: Add new robots to the database (post request).

---

## 🛠️ API Endpoints

### Available Routes

| Method | Endpoint               | Description                           |
|--------|------------------------|---------------------------------------|
| `GET`  | `/api/v1/robots`        | Returns a list of all robots.         |
| `GET`  | `/api/v1/robots/{id}`   | Retrieves details of a specific robot by ID. |
| `POST` | `/api/v1/robots`        | Creates a new robot entry.            |

### Example Request

#### 1. Get all robots

**Request:**
```http
GET /api/v1/robots
