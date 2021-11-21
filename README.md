# React Authentication

### Options

**Local storage:**  easy to implement and use, susceptible to cross-site scripting (high impact)

**Token in cookies:**  harder to implement, susceptible to cross-site request forgery (medium impact)

**Cookies and sessions instead of tokens:** susceptible to cross-site request forgery (potentially high impact)

**Token in auth state:** hardest to implement, potentially susceptible to cross-site scripting but not as much as local storage
