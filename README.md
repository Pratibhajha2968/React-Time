# React-Time
React Series

React Interview Questions

“Can you build a real React app and explain it simply?”

=======================================================================================================================================


🔷 1️⃣ React Hooks
❓ Possible Questions

What are hooks in React?

Why were hooks introduced?

Can we use hooks in class components?

Name some commonly used hooks.

Rules of hooks?

Why hooks are better than classes?

✅ Gap-Friendly Answer

Hooks are functions that allow us to use React features like state and lifecycle in functional components. They were introduced to make code reusable and easier to understand.

📌 Mention:

useState

useEffect

useContext

============================================================================================================================================================

🔷 2️⃣ useState vs useEffect
❓ Possible Questions

What is useState?

What is useEffect?

Difference between useState and useEffect?

When does useEffect run?

What is dependency array?

Can we have multiple useEffect?

✅ Gap-Friendly Answer

useState is used to store and update data in a component.
useEffect is used to perform side effects like API calls or DOM updates.

Example explanation:

useState → form values

useEffect → API calls on page load

=============================================================================================================================================================

🔷 3️⃣ Props vs State
❓ Possible Questions

What are props?

What is state?

Difference between props and state?

Can child modify props?

Why state is important?

✅ Gap-Friendly Answer

Props are used to pass data from parent to child and are read-only.
State is used to manage data inside a component and can be updated.

📌 One-liner:

Props → external
State → internal

=============================================================================================================================================================

🔷 4️⃣ Controlled Components
❓ Possible Questions

What is a controlled component?

Why do we use controlled components?

Controlled vs uncontrolled components?

How do you handle form input in React?

✅ Gap-Friendly Answer

A controlled component is a form element whose value is controlled by React state.

Example explanation:

Input value comes from useState

Changes handled using onChange

====================================================================================================================================================

🔷 5️⃣ Why Keys Are Important
❓ Possible Questions

Why keys are used in React?

What happens if we don’t use keys?

Can we use index as key?

When should we avoid index as key?

✅ Gap-Friendly Answer

Keys help React identify which items have changed, added, or removed. They improve performance and avoid UI bugs.

📌 Mention:

Use unique IDs

Avoid index when list changes

===================================================================================================================================================================

🔷 6️⃣ How API Is Called in React
❓ Possible Questions

How do you call API in React?

Where do you make API calls?

Why use useEffect for API?

Axios vs fetch?

How do you handle loading and error?

✅ Gap-Friendly Answer

API calls are made inside useEffect using fetch or axios to avoid multiple re-renders.

Flow:

useEffect → call API

useState → store data

========================================================================================================================================================

🔷 PRACTICAL REACT QUESTIONS (VERY COMMON)
🔸 7️⃣ How Do You Structure a React Project?
❓ Question

How do you organize your React files?

✅ Gap-Friendly Answer

I structure my project by separating components, pages, services, and styles to keep code clean and maintainable.

Example:

src/
 ├── components/
 ├── pages/
 ├── services/
 ├── hooks/
 ├── assets/
 └── App.jsx

 =================================================================================================================================================================

🔸 8️⃣ How Do You Handle Forms?
❓ Questions

How do you handle forms in React?

How do you validate form inputs?

Controlled vs uncontrolled forms?

✅ Gap-Friendly Answer

I handle forms using controlled components where form data is stored in state and updated using onChange.

Mention:

useState

validation

submit handler

===============================================================================================================================================================

🔸 9️⃣ How Do You Protect Routes?
❓ Questions

What are protected routes?

How do you implement authentication in React?

How do you prevent unauthenticated access?

✅ Gap-Friendly Answer

Protected routes are used to restrict access based on authentication. I check token availability and redirect unauthorized users.

Mention:

React Router

Token

PrivateRoute component

====================================================================================================================================================

🔥 MOST ASKED COMBO QUESTIONS (FOR GAP CANDIDATES)

Explain hooks with example.

How do you call API in React?

How do you manage form state?

Explain protected routes.

Difference between props and state with example.

How is React better than plain JS?

Explain your project architecture.

💡 HOW TO ANSWER CONFIDENTLY (IMPORTANT)

Use this formula:
1️⃣ Simple definition
2️⃣ One real use case
3️⃣ Relate to project

Example:

“In my job portal project, I used useEffect to fetch job data…”
