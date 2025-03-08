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
  Mega Man Robots API is a .NET Core backend service designed to provide JSON-formatted data
  on the bosses and robots from the Mega Man series. Built with .NET Core 3.1 and modern development
  technologies, this API enables efficient data management and serves as an essential resource for
  accessing Mega Man robot data.
</p>

<p align="center">
  <img src="./_docs/assets/carbon.png" alt="API Overview" />
</p>

---

## 🛠️ API Endpoints

| Method | Endpoint               | Description                           |
|--------|------------------------|---------------------------------------|
| `GET`  | `/api/v1/robots`        | Returns a list of all robots          |
| `GET`  | `/api/v1/robots/{id}`   | Retrieves details of a specific robot by ID |
| `POST` | `/api
