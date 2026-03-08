# Bitespeed Identity Reconciliation API

## Endpoint

POST /identify

Example Request

{
 "email":"doc@fluxkart.com",
 "phoneNumber":"123456"
}

Example Response

{
 "contact":{
  "primaryContactId":1,
  "emails":["doc@fluxkart.com"],
  "phoneNumbers":["123456"],
  "secondaryContactIds":[]
 }
}

## Live API

https://YOUR_RENDER_URL/identify
