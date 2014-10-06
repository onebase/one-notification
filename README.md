OneBase - Notification
======================

This is a ready to go notification module which provide email sending service as an API.

## Features

- Email Notification API (port: 8080)
- Administration UI (port: 8090)
- Configurable Email Template
- Integrated with Mailgun, Mandrill and SMTP

## Usage

`
docker run --rm -d -p 8080:8080 8090:8090 -v ~/onebase/notification:/data onebase/notification:latest
`

## Development

```bash
git clone git@github.com:onebase/one-notification.git
cd one-notification
fig up
```
