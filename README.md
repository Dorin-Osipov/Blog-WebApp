# Flask publishing app

Visitors can read articles, registered readers can comment, and an administrator can create, edit or remove posts. The app uses Flask, SQLAlchemy and server-rendered templates.

## Explore the implementation

- [Application and data model](main.py) — the `BlogPost`, `User` and `Comment` models, sign-in routes and `admin_only` decorator.
- [Forms](forms.py) — inputs for registration, editing posts and submitting comments.
- [Article page](templates/post.html) — how an article and its comments are presented to readers.

[Hosted app](https://myblog-app-1fib.onrender.com)
