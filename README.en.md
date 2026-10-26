[Polski](README.md) | **English**

# HTML Portfolio

A multi-page portfolio website in pure **HTML**, built as an exercise in a web development course on linking pages and organising a project into folders.

## Pages

- **`index.html`** — home page with links and preview images of two earlier projects,
- **`public/movie-ranking.html`** — Movie Ranking project (top 3 films),
- **`public/birthday-invite.html`** — Birthday Invite project,
- **`public/about.html`** — About Me,
- **`public/contact.html`** — Contact Me.

`goal.png` and `solution.html` are the reference materials from the course.

## Structure

```
index.html
public/          – subpages
assets/images/   – project previews
```

## Running

The links use root-relative paths (e.g. `/public/about.html`), so open the site through a local server rather than by double-clicking the file — for example the **Live Server** extension in VS Code, or:

```bash
python -m http.server
```

and go to <http://localhost:8000>.
