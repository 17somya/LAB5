# Android Project 5 - Campground Explorer Pt. 2: Offline Mode

Submitted by: **Your Name Here**

**Campground Explorer Pt. 2** is an Android app that extends the National Park Service Campground Explorer App by adding **Offline Mode** using the Room persistence library. Users can now view cached campground data even without internet access.

Time spent: **3** hours spent in total

---

## Required Features

The following **required** functionality is completed:

- [x] **Campgrounds are displayed with name, description, lat/long, and image**
- [x] **Most recent API data is cached into a local Room database**
- [x] **App deletes old entries and inserts fresh data when online**
- [x] **App loads cached campgrounds from Room when offline**
- [x] **Offline functionality works after app restart in Airplane Mode**

The following **optional** stretch features are implemented:

- [ ] Swipe-to-refresh → force a new network call  
- [ ] Shared Preferences toggle to enable/disable caching  
- [ ] Search UI to filter campgrounds or query the API  
- [ ] Connectivity listener → display banner when offline and auto-refresh when back online  

The following **additional** features are implemented:

* [ ] Any other UI or performance improvements (if added)

---

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![LAB5](https://github.com/user-attachments/assets/496fc0b1-0ff8-4b76-9724-a7dd6826e8b7)

https://imgur.com/gallery/lab5-UZMH4n6#b9zg3xd
---

## Notes

Challenges faced while building the app:  
- Understanding how **Room entities, DAOs, and databases** work together  
- Setting up the **Application class** to manage a singleton Room instance  
- Ensuring data consistency by following the **Single Source of Truth** principle  
- Using **Coroutines + Flow** to handle async DB reads/writes without blocking the UI  

---

## License

    Copyright [2025] [Somya Thakkar]

    
