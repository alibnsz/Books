# Books

<p align="center">
  <img width="256" height="256" src="https://github.com/user-attachments/assets/cb7bc836-773a-4a68-9a44-0916186f6c8e" />

</p>

**Books** is a mobile application designed for book enthusiasts. It allows users to **search for books**, **add them to favorites**, **mark them as read**, and manage their personal library. The app retrieves book data from the **Open Library API** and uses a **Node.js backend** with **MongoDB caching** to deliver a fast and optimized experience.

## Features

- **Book Search:** Fast and accurate search powered by the Open Library API.  
- **Favorites:** Save and manage your favorite books.  
- **Mark as Read:** Keep track of your reading history.  
- **Profile Management:** Create and manage your personal reading list.  
- **Optimized Image Handling:** Book covers are loaded quickly using SDWebImage.  

## Technology Stack

- **Mobile (iOS)**  
  - Built with UIKit  
  - **Alamofire** for HTTP requests  
  - **SDWebImage** for efficient image loading and caching  

- **Backend**  
  - **Node.js & Express** for API management  
  - **MongoDB** for data caching  

- **API**  
  - Integrated with **Open Library API**  

## Design

The application design was created using **Figma**, focusing on a clean, user-friendly, and modern interface.

## How It Works

1. The user searches for a book in the app.  
2. The app sends the request to the Node.js backend.  
3. The backend checks MongoDB:  
   - If the data exists, it is returned directly.  
   - If not, it fetches from the Open Library API, stores it in MongoDB, and returns it.  
4. Book cover images are loaded asynchronously and cached using SDWebImage.  

## Screenshots

<p align="center">
<img width="1024" height="1024" src="https://github.com/user-attachments/assets/3de9d17f-292e-4c29-83cc-7c6a0788edde" />
</p>

## Purpose

BooksApp helps users organize their reading habits, manage their favorite books, and build a personal digital library — all while ensuring a smooth and modern user experience.
