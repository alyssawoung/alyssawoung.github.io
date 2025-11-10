# alyssawoung.github.io

body {
  margin: 0;
  font-family: 'Montserrat', Arial, sans-serif;
  background: linear-gradient(135deg, #efb9df, #181718 70%);
  color: #eceded;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #181718;
  padding: 1rem 2rem;
  color: #f1acf1;
  box-shadow: 0 4px 16px rgba(0,0,0,0.15);
}

.navbar-logo {
  font-size: 1.6rem;
  font-weight: bold;
  color: #fab1e0;
  letter-spacing: 2px;
}

.nav-menu {
  list-style: none;
  display: flex;
  gap: 2rem;
}

.nav-menu li a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  padding: 0.6rem 1.1rem;
  border-radius: 6px;
  transition: background 0.2s;
}

.nav-menu li a:hover {
  background: #fab1e0;
  color: #181718;
}

.page-container {
  max-width: 760px;
  margin: 2rem auto;
  background: rgba(30, 28, 38, 0.85);
  padding: 2rem;
  border-radius: 16px;
  box-shadow: 0 2px 12px rgba(255,182,193,0.15);
}
