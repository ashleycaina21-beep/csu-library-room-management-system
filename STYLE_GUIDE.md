# Team Style Guide

## Naming Conventions

### Variables
Use camelCase for variables.

Example:
```js
studentName
userProfile
```

### Components
Use PascalCase for components.

Example:
```js
LoginPage.jsx
DashboardCard.jsx
```

### File Names
Use lowercase with hyphens for folders.

Example:
```txt
student-profile
```

---

## Formatting Rules

- Use 2 spaces indentation
- Use semicolons at the end of statements
- Maximum line length: 100 characters
- Separate logical blocks with blank lines

---

## Commenting Standards

### Function Comments

```js
// Validates user login credentials
function validateLogin() {

}
```

### Inline Comments

```js
// Redirect user after successful login
navigate("/dashboard");
```

---

## Branch Naming Convention

Format:

```txt
feature/feature-name
```

Examples:

```txt
feature/login-page
feature/student-dashboard
fix/navbar-bug
docs/readme-update
```

---

## Commit Message Format

Format:

```txt
type(scope): description
```

Examples:

```txt
feat(auth): add login validation
fix(profile): resolve image upload bug
docs(readme): update installation guide
```
