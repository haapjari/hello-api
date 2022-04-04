# Go Training (2022)

- GoLang Training
- Project is a Tutorial from: [freeCodeCamp's "Learn Go Programming by Building 11 Projects - Full Course"](https://www.youtube.com/watch?v=jFfo23yIWac)

---

## To Run

- `go build` - Starts Server at Port 8080.

---

## Available Endpoints

- Path: `/`, Method: `GET` - Root, serves a Static HTML Page
- Path: `/hello`, Method: `GET` - Returns a Message
- Path: `/form`, Method: `POST` - Returns a HTML Form

Example POST to /form

```
{
    "name": "User",
    "address": "Test Street 1"
}
```

---