# Reaactjs-learning

---

**Theory**

Facebook faced a prblm where real time notifs & reactions weremn't showing, it showed when browser reloaded which lead to whole Main DOM Tree to be reloaded, ts happened bcoz they we using php in the backend

The browser reloads itself/DOM tree when there is even a small change, so
1 change = 1 refresh which is 100,000 changes = 100,000 refreshes!
This will lead to crashing of the Browser!

ts new library which was built by facebook was special, because it was able to show the in real time, ts library wasn't using a real DOM tree, it had a special DOM tree created for itself - it was Virtual DOM

Ts Virtual DOM tree was an exact copy of real DOM but if there were any changes in a paricular component of ts virtual Dom tree, then only the components would've changed/refreshed instead of the whole the Browser

That's why **React** became so famous and useful for big applications, bcus

- it uses Browser Efficiently
- uses Apps Efficiently
- delievers better Experience to the User

Features of React

- very very very less page reload
- extreme use of reusable components
- very very efficient and provide a lot of opportunities
- it will website feel like an App due to less reloads

What - js library to maintain the frontend efficiently(view part mostly), not a language or framework
Why - efficient and lightweight
how use it - create components, and make data if you need it, link the data and change data whenever you want
When to use - when we need to create a app on a bigger level, where a lot of things are going on and where are very much use of reusable components

---

We dont need to write a whole code in react, the facebook has provided a tool to develop which is create-react-app, CRA is working a bit weird so we are using VITE here, it enables us to create a Raw React App
Steps -

- Install Vite
- Create new app

To run use, 
```
npm run dev
```
in terminal

--
**Code Folder Structure**
- Ignore node modules, react app needs it to run basically, no changes are made here
- Public Folder: Images, vids, svg will go here
- src: 
--
