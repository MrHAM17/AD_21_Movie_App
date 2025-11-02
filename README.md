## AD_21_Movie_App

### 📱 Short Description

A sophisticated application that fetches and displays **popular movie data** from an online source (TMDB API) using **Retrofit** and following the **MVVM architecture**.

---

### 🧩 Concepts Covered

* **MVVM Architecture** (Model, View, ViewModel)
* **Retrofit** library for making asynchronous network requests
* **JSON** parsing and converting responses to **POJO** (Plain Old Java Objects)
* **Service Interface** for defining API endpoints (`@GET`, `@Query`)
* **Glide** image loading library
* **Data Binding Adapters** (`@BindingAdapter`) for custom image loading logic
* **Swipe Refresh Layout** (pull-to-refresh functionality)

---

### 🎯 Learning / Discovery Points

* Configuring **Retrofit** with a Base URL and Converter Factory (JSON)
* Defining data models (`Movie`, `Result`) that match the complex nested **JSON response structure**
* Using a **Repository** to manage the remote data source
* Implementing a custom binding logic to construct and load remote images from URLs using **Glide**
* Utilizing a **ViewModel** and **LiveData** to handle data persistence and automatic UI updates from the network response.

---

### ⚙️ App Features / Usage

* Fetches popular movies from the TMDB API.
* Displays movies in a **scrollable grid** (RecyclerView) with poster, title, and average rating.
* Supports **pull-to-refresh** functionality to fetch updated data.

---

### 📝 Note

This project masters several advanced Android concepts: remote data handling, JSON conversion, image loading best practices, and the MVVM architecture.

---
