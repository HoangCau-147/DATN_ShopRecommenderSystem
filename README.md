
# Đồ án Tốt nghiệp
![website](https://img.shields.io/badge/-website-4CAF50)
![ecommerce](https://img.shields.io/badge/-e--commerce-FF9800)
![algorithms](https://img.shields.io/badge/-algorithms-9C27B0)
![react](https://img.shields.io/badge/-react-61DAFB)
![python](https://img.shields.io/badge/-python-3776AB)
![dotnet](https://img.shields.io/badge/-.NET-512BD4)

---
<p align="center">
 <img src="./src/assets/BrandLogos/Logo.png" alt="Logo" height = "400">ShopLY</a>
</p>

<h2 align="center">Store Recommendation System</h2>

---

## 📄 Context
In today’s era of digitalization and rapidly advancing technology, people are increasingly shifting their everyday needs to online platforms—such as making payments, working remotely, and especially shopping online through e-commerce websites, which are growing at a fast and widespread rate. Most types of products are now listed and traded on these e-commerce platforms.

Currently, thousands of e-commerce websites exist both in Vietnam and around the world, offering a wide variety of product categories. However, due to the sheer number and scale of these platforms, many issues still persist—most notably problems related to product and store quality control. In reality, many users have encountered situations where the products they received did not match the description, or they ended up buying counterfeit or low-quality items. Moreover, finding the right product can take a significant amount of time, as users often need to search, compare, and analyze options across multiple stores.

---

## 📄 Introduction
The project is a store recommendation system developed as an e-commerce platform. It delivers personalized suggestions by analyzing user data, such as purchase history, reviews, and other inputs. Store-specific factors, including follower count,ratings, reviews, and other relevant metrics, are also considered to enhance the credibility of recommendations.

---

## 📲System Architecture
<p align="center">
 <img src="/report/systemarchitecture.png" alt="system architecture"></a>
</p>

---

## 📲All Features

The system consists of three main subsystems: Customer Users, Retailers, and Administrators. Each subsystem interacts with the system by performing the following functions:

### Customer Users
* Search for products
* Purchase products
* Add, Delete, Update products in the shopping cart
* View product details

#### Retailers 
* Comment on and rate products
* Manage profile: edit profile, addresses, etc.
* Add, Delete, Update, View products
* View and update order statuses

#### Administrators
* Dashboard management
* Update Neighborhood-based algorithm
* Update Content-based algorithm
* Review and evaluate product comments

## 💻 Technical
* Language: Python • SQL • C# • JavaScript
* Framework: ReactJS • Tailwind CSS
* Database: MS SQL Server • Elasticsearch
* Backend: ASP.NET Core • EF Core • Identity • DI • FastAPI
* Algorithm: Neighborhood CF • Content-based • Matrix Factorization

---

## 💻 Algorithms
* Neighborhood-based Collaborative Filtering
* Content-based Filtering
* Matrix Factorization

---

## 👨‍💻 Members
* NGUYỄN QUỐC ANH – 20120429 
* TÔ TRẦN SƠN BÁ – 20120431 
* HOÀNG  VĂN CẦU – 20120439 
* NGUYỄN ĐÌNH CƯỜNG – 20120446 
* NGUYỄN TRUNG HIẾU – 20120477 
* VƯƠNG TẤN PHÁT – 20120344

---

## Source
### Front-end
https://github.com/HoangCau-147/DATN_ShopRecommenderSystem/tree/Front_end

### Back-end
https://github.com/HoangCau-147/DATN_ShopRecommenderSystem/tree/Back-end

### NLP-model
https://github.com/HoangCau-147/DATN_ShopRecommenderSystem/tree/NLP_model

### Py-server
https://github.com/HoangCau-147/DATN_ShopRecommenderSystem/tree/PyServer

---

## Layer
* The project applies the clean architecture principles to implement the code.

```
└── 📁ShopRecommenderSystem
    └── 📁public
    └── 📁src
        └── 📁assets          => Static resources (images, logos, icons)
            └── 📁BrandLogos
            └── 📁HomeImg
            └── ...
        └── 📁components      => Reusable UI components
            └── 📁Card
            └── 📁Footer
            └── 📁Header
            ├── ...
        └── 📁EventBus        => Event-based communication between components
        └── 📁HOC             => Higher-Order Components for extra logic
        └── 📁layouts         => Page layout templates
            └── 📁DefaultLayout
            └── 📁HeaderOnly
            ├── index.js
        └── 📁pages           => Individual page components (views/screens)
            └── 📁AdminDoashboard
            └── 📁Login
            └── ...
        └── 📁routes          => App routes mapping URLs to pages
        └── 📁services        => API services for backend communication
            └── 📁AdminApi
            └── 📁CheckoutApi
            └── ...
            ├── axios-customize.js
        └── 📁styles          => Global CSS and resets
            ├── global.css
            ├── reset.css
        ├── App.css
        ├── App.js
        ├── index.css
        ├── index.js
        ├── cloudinaryConfig.js
    └── tailwind.config.js
```

---

## 📱 UI

| Page1 | Page2 | Page3 |
|:--:|:--:|:--:|
| ![image](report/Ảnh1.png) | ![image](report/Ảnh2.png) | ![image](report/Ảnh3.png) |
| ![image](report/Ảnh4.png) | ![image](report/Ảnh5.png) | ![image](report/Ảnh6.png) |
| ![image](report/Ảnh7.png) | ![image](report/Ảnh8.png) | ![image](report/Ảnh9.png) |
| ![image](report/Ảnh10.png) | ![image](report/Ảnh11.png) | ![image](report/Ảnh12.png) |
| ![image](report/Ảnh13.png) | ![image](report/Ảnh14.png) | ![image](report/Ảnh15.png) |
| ![image](report/Ảnh16.png) | ![image](report/Ảnh17.png) | ![image](report/Ảnh18.png) |
| ![image](report/Ảnh19.png) | ![image](report/Ảnh20.png) | ![image](report/Ảnh21.png) |
| ![image](report/Ảnh22.png) | ![image](report/Ảnh23.png) | ![image](report/Ảnh24.png) |
| ![image](report/Ảnh25.png) | ![image](report/Ảnh26.png) | ![image](report/Ảnh27.png) |
| ![image](report/Ảnh28.png) | ![image](report/Ảnh29.png) | ![image](report/Ảnh30.png) |
| ![image](report/Ảnh31.png) | | |

---

## 📺 Video demo
https://youtu.be/G3f2FhrMlRs