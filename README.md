# JUNIORS
Personal Project
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  My Homepage
</head>
<body>
  <header>
    <h1>Welcome to My Site!</h1>
    <nav>
      <a href="/about.html">About</a>
      <a href="/contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <p>This is the homepage. Add your main content here.</p>
  </main>
  <footer>
    <p>&copy; 2025 My Site</p>
  </footer>
</body>
</html>

export default function Home() {
  return (
    <div>
      <header>
        <h1>Welcome to My Site!</h1>
        <nav>
          <a href="/about">About</a>
          <a href="/contact">Contact</a>
        </nav>
      </header>
      <main>
        <p>This is the homepage. Add your main content here.</p>
      </main>
      <footer>
        <p>&copy; 2025 My Site</p>
      </footer>
    </div>
  )
}
