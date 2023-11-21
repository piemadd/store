# Store

Store is meant to be a system allowing for large amounts of semi-related to be
consolidated into a single API. The original purpose of this API was for me to
expand my transit tracking tooling to systems besides Amtrak. However, I
realized that this could be used for other things as well, such as weather data.

More documentation is yet to come.

## Environment Variables

For all endpoints to run, store needs a few environment variables, but won't die
if one of these is missing (it'll simply skip any endpoints which don't have
their required variables).

Those are:

- `metra_authorization`
- `cta_bus_auth`
- `bsky_holiday_bot_handle`
- `bsky_holiday_bot_password`
