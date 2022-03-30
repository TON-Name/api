# TON Name API
Public API of the TON Name service

## Authorization
You do not need to get a token to access our API. You can use it without authorization.

## Rate limit
2 requests per second

## Endpoint
``https://api.tonname.tech``

## Methods
### GET /api/getName
Get user nickname by wallet address
#### Query params
| Param   | Type   | Description                                                   |
|---------|--------|---------------------------------------------------------------|
| address | String | Address of the user's account whose nickname you want to find |

### GET /api/getAddress
Get user wallet by name
#### Query params
| Param | Type   | Description                                        |
|-------|--------|----------------------------------------------------|
| name  | String | The name of the user whose wallet you want to find |
