FROM hashicorp/terraform:0.11.11

LABEL "com.github.actions.name"="terraform plan"
LABEL "com.github.actions.description"="Run terraform plan"
LABEL "com.github.actions.icon"="book-open"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/hreeder/terraform-github-actions"
LABEL "homepage"="http://github.com/hreeder/terraform-github-actions"
LABEL "maintainer"="Harry Reeder <harry@harryreeder.co.uk>"

RUN apk --no-cache add jq

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
