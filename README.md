[![Build Status](https://travis-ci.com/LivingNebula/LivingNebula.svg?token=e6dosT2N6x49im7Ffzix)](https://travis-ci.com/LivingNebula/LivingNebula)[![Coverage Status](https://coveralls.io/repos/LivingNebula/LivingNebula/badge.svg?branch=master&service=github)](https://coveralls.io/github/LivingNebula/LivingNebula?branch=master)

# Living Nebula Productions Main Site

## Installation

Required Environment Variables
-DEBUG

Install requirements

    $ pip install -r requirements.txt
    $ pip install -r requirements_test.txt
    
Perform management tasks

    $ python manage.py syncdb
    $ python manage.py migrate
    $ python manage.py collectstatic --no-input

## Settings

No local settings file is required. There is a section of settings.py for local settings which checks
"if DEBUG:". Feel free to modify this section locally, but be sure not to commit any of these local changes.
