# 📱 AR Project — “Living Photo Albums”

**AR Project** is a mobile augmented reality application that brings school photo albums to life using QR codes and computer vision.

---

## 🚀 How It Works

1. **Launch the app**  
   When the application starts, a frame appears on the screen where the user needs to place the QR code of a school album.  

2. **QR‑based authorization**  
   The QR code is generated only by the album creator and is used for private access.  
   It encrypts a JSON file that contains:  
   - links to images and videos,  
   - the physical dimensions of the photos.  

3. **Content loading and caching**  
   After scanning, the app fetches trigger photos and videos from **Yandex Cloud** and caches them for offline use, so they don’t need to be downloaded again.  

4. **Trigger recognition**  
   The user points the smartphone camera at a photo (in the printed album, on regular paper, or even on a monitor).  
   - When the trigger image is recognized, the associated media content is played.  
   - The static photo “comes alive” in real time.  

---

## ✨ Features

- Recognizes photos from different sources: screens, photo paper, or plain paper.  
- Works even under **minimal lighting conditions**.  
- Robust to noise: recognition succeeds even if the photo has extra elements (logos, drawings, frames) as long as the background differs from the original trigger image.  
- **Privacy‑first**: the QR code is generated only by the album creator and is not distributed publicly.  

---

## 🎯 Purpose

- Makes school albums **interactive and dynamic**.  
- Preserves and replays memories in an AR format.  
- Can be adapted for educational, marketing, or creative projects.  

---

## 🛠️ Technologies

- **Unity + AR Foundation** — cross‑platform AR (Android/iOS).  
- **ARCore / ARKit** — native augmented reality frameworks.  
- **Yandex Cloud** — media storage and delivery.  
- **QR code** — secure access and album binding mechanism.  

---

## 📦 Installation & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/FilippFprog1/AR_project.git
