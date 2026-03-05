## API Design & Endpoints

| Feature | Method | Endpoint | Description |
| :--- | :--- | :--- | :--- |
| **List All** | `GET` | `/api/assignments` | Fetches all logs from `data.json`. |
| **New Entry** | `POST` | `/api/assignments` | Creates a new assignment (Status: `Create`). |
| **Detail** | `GET` | `/api/assignments/{id}` | Gets a single assignment by ID. |
| **Update Status**| `PATCH`| `/api/assignments/{id}` | Updates status to `On Process` or `Submitted`. |
| **Remove** | `DELETE`| `/api/assignments/{id}` | Deletes an assignment. |
