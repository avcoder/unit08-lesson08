---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /assets/intro.jpg
# some information about your slides (markdown enabled)
title: Software Development | Foundations
info: |
  ## Software Development | Foundations
# apply unocss classes to the current slide
class: text-left
drawings:
  persist: false
transition: slide-left
mdc: true
---

# React Native
Mobile Development: Unit 08 - Lesson 08

- [ ] Capstone Q&A
- [ ] Continue playing with expo APIs 
- [ ] Create own app

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
-->
---
transition: slide-left
---

# Capstone 
Let's take a closer look in the LMS at 3 things: Capstone Planning, Capstone Project, Mobile Assignment

- Review the ideas and requirements for the capstone project.
   - see https://unit09-capstone.netlify.app/
- What would employers want to see?
- Capstone Planning due Sept 28
- Capstone Project due Oct 23

## Mobile Assignment 
   - due Oct. 5 (not a hard due date, since you can submit this later if you wish to submit Capstone first)

---
transition: slide-left
---

# Leave a Review

- https://docs.expo.dev/versions/latest/sdk/storereview/

---
transition: slide-left
---

# Maps

- `npx expo install react-native-maps`
- see https://docs.expo.dev/versions/latest/sdk/map-view/
```tsx
import MapView from 'react-native-maps';

export default function App() {
  return (
    <View style={styles.container}>
      <MapView style={styles.map} />
    </View>
  );
}
```

- [Register](https://console.developers.google.com/apis) a Google Cloud API project and enable the Maps SDK


---
transition: slide-left
---

# Different Ways to Store Data Locally

- see https://docs.expo.dev/develop/user-interface/store-data/
- SecureStore: https://docs.expo.dev/versions/latest/sdk/securestore/
- SQLite: https://docs.expo.dev/versions/latest/sdk/sqlite/

---
transition: slide-left
---

# SMS

- see https://docs.expo.dev/versions/latest/sdk/sms/

---
transition: slide-left
---

# ImagePicker

- see https://docs.expo.dev/versions/latest/sdk/imagepicker/

---
transition: slide-left
---

# 3rd party packages

- [react-native-game-engine](https://www.npmjs.com/package/react-native-game-engine)
   - Gives you a basic game engine to build simple 2D games.
   - Create a Flappy Bird or Pong clone
- [react-native-vision-camera](https://www.npmjs.com/package/react-native-vision-camera)
   - Access the device camera with superpowers (faster, more extensible).
   - Make a fun camera filter app like Snapchat lenses
- [react-native-gesture-handler](react-native-gesture-handler)
   - Adds gesture capabilities like swipe, pinch, drag.
- [flash-list](https://www.npmjs.com/package/@shopify/flash-list)
   - high-performance lists (superior to FlatList for large data)
- [lottie-react-native](https://www.npmjs.com/package/lottie-react-native)
   - parses Adobe After Effects animations exported as JSON and renders them natively


---
layout: image-right
transition: slide-left
image: /assets/dan.png
backgroundSize: 444px 300px
class: text-left
---

# 10 minute break

🍦 Cool Tips, Trends and Resources:
- 🪏 [Why we ditched Next.js](https://northflank.com/blog/why-we-ditched-next-js-and-never-looked-back)
- ⚡ [content-visibility: auto](https://cekrem.github.io/posts/content-visibility-auto-performance/)
- 🎭 [React for Two Computers](https://www.youtube.com/watch?v=ozI4V_29fj4)
- ⚛️ [JSX Over the Wire = RSC](https://overreacted.io/jsx-over-the-wire/)
- 🍎 [new MAC setup](https://www.swyx.io/new-mac-setup)


<br>
<hr>
<br>

- 🧪 [Enter anonymous lab questions](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)
- ℹ️ [Course feedback survey](https://circuitstream.typeform.com/to/ZoyYk7px#course_id=SoftwareAN&instructor=9514)

---
transition: slide-left
---

# Exercise: Create your own app
Try one of the following:

1. Continue with https://thecatapi.com/ OR https://thedogapi.com/
   - Create functionality to "Vote on Images and get Historic Votes”
   - see https://developers.thecatapi.com/view-account/ylX4blBYT9FaoVd6OhvR?report=bOoHBz-8t
2. Build a mini restaurant app with four buttons, images of three or four dishes. 
   - see https://github.com/Circuit-Stream-LMS/menu-app-starter


---
transition: slide-left
---

# Homework

- Start working on your Mobile Assignment 
- Start working on your Capstone planning project
