## setup
* install terraform (mac): `brew install terraform`
* set AWS credentials as envvars:
`export AWS_ACCESS_KEY_ID=<key> &&
export AWS_SECRET_ACCESS_KEY=<secret>`

## assess
* initialize: `terraform init`
* check what you're about to do: `terraform plan`
* get DOT that can be rendered by graphviz: `terraform graph`

## deploy
* `terraform apply`