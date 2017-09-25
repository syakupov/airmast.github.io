isotherm_lower
=====

Set isotherm lower value
-----------------

Request Type | URL | Supported DJI Zenmuse
-------------|-----|-----------------------
POST | **/api/v1/isotherm_lower/`<value>`** | XT

`<value>` &mdash; integer value of isotherm (from -40 to 1000)

**Note:** This setting takes effect only if [isotherm](/camadapter/api/isotherm/) is enabled.

### Sample Request

```http
POST http://localhost:8123/api/v1/isotherm_lower/90
```

### Sample Response

Status code: **200**

```javascript
{
    "success": true
}
```
