# How to Update Your Personal Blog Example

These steps show how to recreate or modify the sample **Personal Blog** provided in this repository.

## 1. Copy the Example
Use the existing `index.html` from the `personal-blog` directory as a starting point. This file contains a minimal blog layout with two sample posts.

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Frontend Mentor | Personal Blog</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        max-width: 800px;
        margin: 0 auto;
        padding: 2rem;
        line-height: 1.6;
      }
      header {
        text-align: center;
        margin-bottom: 2rem;
      }
      article {
        margin-bottom: 2rem;
      }
      article h2 {
        margin-bottom: 0.5rem;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>My Personal Blog</h1>
      <p>Welcome to my Frontend Mentor challenge.</p>
    </header>
    <main>
      <article>
        <h2>First Post</h2>
        <p>This is a placeholder post for the Personal Blog challenge.</p>
      </article>
      <article>
        <h2>Another Post</h2>
        <p>Continue adding posts as you build out the design.</p>
      </article>
    </main>
  </body>
</html>
```

## 2. Add Your Posts
Replace the sample `article` elements with your own blog posts. Each post uses the following structure:

```html
<article>
  <h2>Your Post Title</h2>
  <p>Post content goes here.</p>
</article>
```

## 3. Customize Styles
The page uses inline CSS for simplicity. Feel free to edit the style block in `index.html` or move the styles to a separate CSS file for larger projects.

## 4. View Your Blog
Open `index.html` in a browser to see your changes. When you're ready to publish, upload this file (and any assets) to your preferred hosting service.

