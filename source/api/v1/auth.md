## Login

This endpoint is for signing into app.

### HTTP Request

`POST /auth/login`

```json
{
	"email" : "binny1@email.com",
	"password" : "binny"
}
```

### HTTP Response

```json
{
  "access_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2Mzg1NDE0NDcsImlkIjoxLCJ0eXBlIjoiMiJ9.JccaF0chzMtBbtL8ZQv9mWUoQ2auTlE3CGuKSMHOAmA",
  "refresh_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2NDI0MjU4NDcsImlkIjoxfQ.U4fqB2VINst5xgbO0YXzTZMPchP7gf3nCljAEhDuP-w"
}
```

---

## OTP auhentication

This endpoint is for authentication through mobile number using OTP.

### HTTP Request 

`POST /auth/otp`

### HTTP Response
