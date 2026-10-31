# Part 2: Day Exercise _ API parameter Descriptions

This exercise bridges micro-content with your upcoming API Reference project. In API documentation, parameter tables must clearly state what data type a field acepts, whether it is requires, and what it does_using concise, active phrasing.

Scenario: Dcumenting the query parameters

You are writing the parameter documentation for a user search endpoint (GET/V1/users/search).

Rewrite the following raw, passive parameter descriptions into clear, standard technical documentation entries.

1. limit Parameter
Raw Draft: This parameter is used by the client to define how many items are returned in the response list. It defaults to 20 if omitted by you. The maximum value that can be set is 100.

Task: Rewrite into a concise 1_2 sentence description. State default and maximum limits clearly.

2. status Parameter
Raw Draft: The filtering of users can be done with this string based on account staUtus. Allowed values are active, pending, or suspended.
 
 Task: Rewrite using active voice. List allowed values clearly.

 3. Created_after Parameter
 Raw Draft: It is required that an ISO 8601 date format is provided if you want to filter results to only users registered after a specific date.
 Task: Rewrite into direct imperative/active voice, specifying the required date format clearly. 


---
 
| Parameter | Type | Required? | Description |
| :--- | :--- | :--- | :--- |
| limit | Integer | Optional | Use this parameter to define how many items return in the reponse list. Default: 20 Max: 100 |
| status | String | Optional | Use this string to filter users by account status. Allowed values are active, pending, or suspending |
| created_after | String (ISO 8601) | Optional | Provide an ISO 8601 to filter results to users registered after a specific date |

---
 
 # Technical Writing Exercises Proposal

 | Parameter | Type | Required? | Description |
 | :--- | :--- | :--- | :--- |
 | `limit` | Integer | Optianal | Sets the maximum number of items returned in the response list. **Default:** `20`. **Maximum:** `100`. |
 | `status` | String | Optinal | Filters users by account status. Allowed Values: `active`, `pending`, or `suspended`. |
| `created_after` | String (ISO 8601) | Optional | Filters results to include only users created after the specified timestamp (for example, `2026-10-30T00:00:00Z`). |

