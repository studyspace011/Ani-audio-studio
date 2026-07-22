# 🎧 Ani Audio Studio (English Department Audio Player)

**Ani Audio Studio** ek lightweight, responsive, aur PWA-enabled Web Audio Player hai, jise **English Department** ke audio lecture notes aur syllabus resources ke liye customize karke design kiya gaya hai. 

Is player ka UI modern audio apps (Spotify-style) se inspired hai, jisme dark/light mode toggle, dynamic section selector, progress tracking, aur offline PWA support shamil hai.

---

## 📌 Features

* 📱 **Mobile-First & PWA Ready**: Mobile screens ke liye optimized bottom drawer navigation aur home screen pe as an App install karne ka option.
* 🎧 **Spotify-Inspired UI**: Clean design, responsive audio controls, seek bar, aur smooth animations.
* 🔄 **Auto-Resume Playback**: Local Storage tracking ki madad se user jahan audio pause karega, next session me audio wahi se resume hoga.
* 📂 **Structured Syllabus Sections**: 
  - `MJC-5`: American Literature
  - `MJC-6`: Language and Linguistics
  - `MJC-7`: British Poetry and Drama (17th Century)
  - `MIC-4`: Study of Urdu Ghazal
  - `AEC-4`: Social Service / Scout & Guide / Sports
* 📥 **Single & Bulk Downloads**: Audio files ko individual play/download karne ke sath poore section ko ek sath download karne ka option.
* 🌙 **Dark / Light Mode**: Dynamic theme switcher toggle.

---

## 📁 Repository & Folder Structure

Audio files ko smoothly link karne ke liye directory structure is tarah organized rakha gaya hai:

```text
ani-audio-studio/
├── index.html
├── README.md
└── audio/
    ├── mjc-5/
    │   ├── 1.1.mp3
    │   ├── 2.1.mp3
    │   └── ...
    ├── mjc-6/
    │   ├── 1.1.1.mp3
    │   └── ...
    ├── mjc-7/
    │   └── ...
    ├── mic-4/
    │   └── ...
    └── aec-4/
        └── ...
