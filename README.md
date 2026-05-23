# qd-templates

Personal QD template repository for website check-in templates.

## Templates

- `司机社_xsijishe_k_misign签到.har`

## Usage

Register this repository in QD as a template source, then import the template
you need from the repository.

For `司机社_xsijishe_k_misign签到.har`, set the `cookie` variable to a valid
`xsijishe.com` login cookie before running it.

The template opens the check-in page, extracts Discuz `formhash`, calls the
`k_misign` check-in endpoint, and then verifies the check-in result from the
daily sign page.
