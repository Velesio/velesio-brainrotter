This project was inspired by Benjamin Keating's youtube video on creating AI Brainrot programatically for social media.

The goal is to automate the setup by providing a docker compose stack, its split into two components in case you want to separate the frontend from the worker GPU backend, but you can also host both on the same machine.
For example I used the frontend.yml to host all the n8n frontend and storage and a GPU backend would activate only intermittently when generating a bunch of videos, to be then prepared for uploading.

Link to Benjamin's video: https://www.youtube.com/watch?v=sOylPpFyQ8A
