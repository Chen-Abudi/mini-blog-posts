# mini-blog-posts

## 📣 Overview:

- Intro
- Tech Stack
- Techniques
- Live Project
- Additional Link

## 🔎 Intro:

A practice project in React, showcasing blog posts. The main purpose of this is on deployment.

## 🧰 Tech Stack:

- React
- React Router Dom v6
- JavaScript
- CSS Modules
- Firebase & Hosting

## 🛠️ Techniques:

- **_`Lazy Loading`_**

- **`React Router Dom Components`**:
  - **_NavLink_**: Is used for navigation between pages.
  - **_Outlet_**: Is a component provided by React Router that serves as a placeholder for child routes within a parent route.
- **`React Router Dom Hooks`**:

  - **_useLoaderData_**: Is a hook that helps to fetch the data for the component before it renders. It improves performance and prevents empty states.

    **`Note`**: This hook can be used only in the element that's assigned to a route AND in all components that might be used inside that element but not on a higher level route.

- **`React Components`**:

  - **_Suspense_**: Is a built-in React component which lets us temporarily render a fallback UI while its children are still loading.
  - **_lazy()_**: Enables code-splitting by allowing components to be loaded lazily. This means the component is only loaded when it's needed, which can improve performance.

    **`Note`**: It's used with **Suspense** to display a fallback while the lazy-loaded component is being fetched.

---

# 🚀 Live Project:

- `Visit the Demo Project` [&#128073;&#127997; **HERE !**](https://blog-posts-demo.web.app)

---

## 🔗 Additional Link:

If you want to strengthen your knowledge and skills of **React, Redux, and more...** along the **Best Practices**, Feel free to check this course on Udemy by **`Maximilian Schwarzmüller`**:

## Visit the Course [&#128073;&#127997; **HERE !**](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)

**_`Shoutout to Maximilian Schwarzmüller for this deployment practice project, all the lectures, the exercises, and the React course in Udemy. Mahalo, Thank you!`_** 🌺
