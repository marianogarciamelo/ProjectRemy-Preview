# ProjectRemy 🍳📸

A social cooking app where users post photos of what they're eating, creating an authentic space to share home cooking experiences with friends — inspired by BeReal and Beer Buddy.

---

## 🚧 Project Status

**Core App: Production Ready** ✅
- Full photo posting, recipe creation, and camera integration
- Smooth local experience with instant UI updates
- Industry-standard local-first architecture

**Social Backend: In Progress** 🔄
- Firebase infrastructure and data models complete
- Image upload pipeline operational
- Cross-user feed synchronization needs completion

---

## ✅ Working Features

- 📸 **Camera Integration** - Native iOS camera with photo capture
- 🍳 **Recipe Creation** - Full recipe builder with ingredients and instructions
- 📝 **Post Creation** - Photo posts with captions and optional recipes
- 📱 **Local Data Persistence** - Instant saves with UserDefaults caching
- ☁️ **Background Cloud Sync** - Firebase integration with offline-first design
- 🎨 **Clean SwiftUI Interface** - Tab navigation following iOS design patterns

---

## 🔄 Social Features (Coming Soon)

- 👥 **Friend System** - Connect with friends for curated feeds
- ❤️ **Likes & Comments** - Social engagement on posts
- 🔔 **Real-time Updates** - Live notifications for friend activity
- 📚 **Recipe Discovery** - Browse and save friends' recipes
- 🔍 **Search & Filter** - Find posts by ingredients, users, or tags
- 🤖 **AI-Powered Search** *(future goal)* - Smart recipe recommendations

---

## 🏗️ Technical Architecture

**Local-First Design**
- Instant UI updates (like Instagram/TikTok)
- Smart caching with Firebase + UserDefaults hybrid
- Background upload pipeline for seamless sync

**Tech Stack**
- **Frontend**: SwiftUI + MVVM Architecture
- **Backend**: Firebase (Firestore, Storage, Auth)
- **Local Storage**: UserDefaults with JSON encoding
- **Authentication**: Firebase Anonymous Auth + Phone verification
- **Images**: Firebase Storage with local caching

**Data Flow**
```
User Action → Local Cache (instant UI) → Firebase Sync (background)
```

---

## 📱 Current Capabilities

This app works fully as a **standalone cooking journal** where users can:
- Take photos of meals and add detailed recipes
- Build a personal cooking history
- Create and organize recipe collections
- Export data (recipes stored as structured JSON)

The social features will connect these individual experiences into a shared community.

---

## 📸 Screenshots

<br/>
<p align="center">
  <img src="./IMG_2542.png" alt="Camera View" width="300"/>
  <br/>
  <br/>
  <em>In-app camera view for capturing meal photos before posting.</em>
</p>
<br/>
<p align="center">
  <img src="./IMG_2543.png" alt="Post Creation UI" width="300"/>
  <br/>
  <br/>
  <em>Post creation interface with caption and optional recipe text input.</em>
</p>
<br/>

---

## 👨‍💻 Developer

Created by **Mariano Garcia-Melo**  
Computer Science Student | iOS Developer | Builder of Clean UI Experiences

📬 garciamelomariano@gmail.com  
🔗 [linkedin.com/in/mariano-garcia-melo](https://linkedin.com/in/mariano-garcia-melo)  
💻 [github.com/marianogarciamelo](https://github.com/marianogarciamelo)

---

## 💡 Inspiration

ProjectRemy was inspired by a personal realization after studying abroad in Rome — seeing how strongly many European cultures value home cooking, fresh ingredients, and intentional eating. In contrast, it became clear how common it is in the U.S., especially among younger generations, to rely on eating out or ordering in.

This app was created to help shift that mindset — to **encourage cooking at home**, to **romanticize everyday meals**, and to make cooking feel fun, expressive, and worth sharing. It's about building a space where friends can swap recipes, share what they're making, and form a community around the joy of everyday food.

Apps like **BeReal** and **Beer Buddy** helped shape the vision — showing how casual, social sharing can build real connections. ProjectRemy brings that same energy, but focuses it on food, creativity, and homegrown moments.

---

## 📝 Notes

> ⚠️ **Note:** This is a public preview of ProjectRemy.  
> The full codebase is private and available upon request for portfolio review.
