# Screendoor SDK for Python

## Install
> $ pip install -e "git://github.com/SFDigitalServices/screendoor-sdk-py#egg=screendoor-sdk"

## Example Usage
> from screendoor_sdk.screendoor import Screendoor

> scrndr = Screendoor(`API_KEY`)

> responses = scrndr.get_project_responses(`PROJECT_ID`, {'per_page': 1, 'page' : 1}, 1)
