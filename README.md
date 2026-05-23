# qd-template-xsijishe

QD template repository for xsijishe.com daily check-in.

## Templates

- `司机社_xsijishe_k_misign签到.har`

## Usage

Import the HAR template into QD and set the `cookie` variable to a valid
`xsijishe.com` login cookie.

The template opens the check-in page, extracts Discuz `formhash`, calls the
`k_misign` check-in endpoint, and then verifies the check-in result from the
daily sign page.
