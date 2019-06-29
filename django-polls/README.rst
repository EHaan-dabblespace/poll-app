=====
Polls
=====

Polls is a simple Django app to conduct Web-based polls. For each question, visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick Start
-----------

1. Add "poll_app" to your INSTALLED_APPS setting like this:
    INSTALLED_APPS = [
        ...
        'poll_app',
    ]

2. Include the poll_app URLconf in your project urls.py like this:
    path('poll/', include('poll_app.urls'))

3. Run `python manage.py migrate` to create the polls models.

4. Start the development server and visit http://127.0.0.1/admin/ to create a poll (you'll need the admin app enabled).

5. Visit http://127.0.0.1:8000/poll/ to participate in the poll.

