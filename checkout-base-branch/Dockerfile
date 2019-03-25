FROM alpine:latest

LABEL version="1.0.0"
LABEL repository="http://github.com/bennycornelissen/github-actions"
LABEL homepage="http://github.com/bennycornelissen/github-actions"
LABEL maintainer="Benny Cornelissen"
LABEL "com.github.actions.name"="Checkout base branch"
LABEL "com.github.actions.description"="Automatically checkout base branch"
LABEL "com.github.actions.icon"="git-pull-request"
LABEL "com.github.actions.color"="purple"

RUN apk --no-cache add jq bash curl git

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
