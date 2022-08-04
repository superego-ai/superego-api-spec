
# Superego API Spec

The [Stone IDL](https://github.com/dropbox/stone) specification that defines
the Superego API.

In short, the API endpoint is at `https://api.superego.ai` and it is JSON-in
and JSON-out with structures defined in Stone.

As a developer, see routes marked with the attribute `auth="user_optional"` as
these can be used without any authentication. If you would like per-user OAuth
access, send us an email at `hi@superego.ai` with your use case.

There is no official commitment for backwards compatibility at this time and
no SDKs are provided.
