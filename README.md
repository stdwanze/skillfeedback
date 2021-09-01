# skillfeedback

clone this repo somewhere.

create a EMPTY folder /path/to/moodle (not same as clone path)
edit docker-compose.yml so that source match /path/to/moodle

run in shell:
docker-compose up -d

wait until /path/to/moodle is populated and moodle is available under "localhost" in browser. 

clone again in /path/to/moodle/local

for changes to take effect, reload moodle
