# Technical writing exercise - Day 2: API Description

---

 | Parameter | Type | Required? | Description |
 | :--- | :--- | :--- | :--- |
 | `limit` | Integer | Optianal | Sets the maximum number of items returned in the response list. **Default:** `20`. **Maximum:** `100`. |
 | `status` | String | Optinal | Filters users by account status. Allowed Values: `active`, `pending`, or `suspended`. |
| `created_after` | String (ISO 8601) | Optional | Filters results to include only users created after the specified timestamp (for example, `2026-10-30T00:00:00Z`). |

