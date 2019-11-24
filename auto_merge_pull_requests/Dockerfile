FROM python:3-alpine

MAINTAINER Alex Chan <alex@alexwlchan.net>

LABEL "com.github.actions.name"="Auto-merge pull requests"
LABEL "com.github.actions.description"="Merge the pull requests"
LABEL "com.github.actions.icon"="activity"
LABEL "com.github.actions.color"="green"

COPY merge_pr.py /
ENTRYPOINT ["python3", "/merge_pr.py"]
