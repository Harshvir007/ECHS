# ECHS

*Architecture Diagram*

<img width="686" height="317" alt="image" src="https://github.com/user-attachments/assets/11775bc1-cd8f-410b-8b83-7bc93d00e07f" />

Salient features:

We use DTO's here

Reason for using DTO's
  1. Keeps teh internal domain models(your database entities) hidden from the client. This protects your app's internal strucutre
  2. Allows you to send or receive only the fields relvant to the client, rather than exposing all fields in your domain model
  3. Request DTO's allow you to validate client input(eg checking if fields are null or meet certain criteria)
