
# Level 1 — Understanding the Repository

### Objective

Explain the structure of the repository.

The candidate should open the project and explain what the following parts do:

Example structure:

```
app/
components/
public/
styles/
package.json
next.config.js
```

### Questions

Ask the candidate:

1. What is the **app folder** used for in Next.js?
2. What is the difference between **server components and client components**?
3. What is the purpose of the **public folder**?
4. What does **package.json** do?

### What we evaluate

We are checking whether the candidate understands:

• modern React / Next.js basics
• project structure
• how Next.js applications are organized

---

# Level 2 — Coding Task

### Task

Create a **new page** that displays a list of users.

### Route

Create the following page:

```
/users
```

### Requirements

Create a page that fetches and displays users from the following API:

```
https://jsonplaceholder.typicode.com/users
```

Each user card should display:

```
Name
Email
Company Name
```

### Example UI

```
Users

John Doe
john@example.com
Company: Example Corp

Jane Smith
jane@example.com
Company: Smith Industries
```

### Requirements

• Fetch data from the API
• Display users in a list or cards
• Use a **React component** for each user
• The page should not reload when navigating

### Bonus

Add simple styling using:

• CSS
• Tailwind
• or inline styles

---

# Level 3 — Interactive Feature

### Task

Add a **search filter** to the users page.

### Behavior

The user should be able to type into a search bar and filter users by name.

Example:

```
Search: jo
```

Results:

```
John Doe
Johnny Smith
```

### Requirements

• Add a search input
• Filter the user list in real time
• Use React state

Example UI:

```
Search Users

[ Search Input ]

John Doe
john@example.com

Johnny Smith
johnny@example.com
```

### What we evaluate

We want to see whether the candidate understands:

• React state
• filtering arrays
• component updates
• writing readable code

---

# What We Look For

Strong candidates typically:

• Ask clarifying questions
• Write clean components
• Use meaningful variable names
• Separate UI into components
• Handle loading states

Weak candidates often:

• Write everything inside one file
• Ignore errors or loading states
• Hardcode values instead of using fetched data

---

# Optional Discussion Questions

If the candidate completes all levels, ask:

1. How would you **cache the API response**?
2. How would you **add pagination**?
3. How would you **fetch the data on the server instead of the client**?

---

If you'd like, I can also create a **much stronger “startup-level” Next.js interview challenge** (about 10× better at detecting real talent) that tests:

• React architecture
• API routes
• state management
• performance
• debugging

It’s the type of test companies like **Vercel and YC startups use**.
