# Metelik_App

 ![img](https://img.shields.io/badge/language-kotlin-blue) ![img](https://img.shields.io/badge/minSDK-26-orange) ![img](https://img.shields.io/badge/androidGradleVersion-4.2.1-green) ![img](https://img.shields.io/badge/gradleVersion-6.7.1-informational)

The Metelik App consists a combination of several Huawei Kits and Services such as Account Kit, Auth Service, Location Kit, Map Kit, Site Kit, Nearby Service and Cloud Database.

<img src="/screenshots/Screenshot_20210902_145133_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_153449_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_161310_com.huawei.app.metelik.jpg" width=200></img>

## Introduction

Metelik App is an Android application that is developed with Huawei Mobile Services. It reveals the markets and cafes around a certain radius of the user's current location by a background notification system. This way, users will be able to easily find markets and cafes near them. The application also offers users the feature of which market or cafe is the cheapest for the product they want to search. In addition, users can upload products that are on sale to the system by logging in with their Huawei ID. Users can add products under predetermined categories such as cafes and markets. Users can follow the prices of the products they want to keep track of, by adding them to their favorites without having to search. If the price of a product is written incorrectly, users will be able to report it. That means that the price of the product with a high number of reports is very likely to be wrong. In addition, users can have information about the average price of the product by looking at the price history of the product.

## About HUAWEI Account Kit

The Account Kit provides easy, safe and fast registration to the user. Users can simply touch the Sign In with HUAWEI ID button to sign in with their HUAWEI IDs in the app easily and safely rather than inserting their credentials and wasting their time for authentication. To discover more, visit: [Huawei Account Kit Guide](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/introduction-0000001050048870)

## About HUAWEI Auth Service

Auth service provides multiple authentication methods to help developers secure user data based on simple rules. Developers can involve one or more of the authentication methods into their applications by using the AppGallery Auth Service SDK to accomplish quick and reliable registration and sign-in for users. To discover more, visit: [Huawei Auth Service Guide](https://developer.huawei.com/consumer/en/doc/development/AppGallery-connect-Guides/agc-auth-introduction-0000001053732605)

## About HUAWEI Map Kit

Map Kit is an SDK for map development. It covers map data of more than 200 countries and regions, and supports over one hundred of languages. With this SDK, the developers can easily integrate map-based functions into their apps. To discover more, visit: [Huawei Map Kit Guide](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides-V5/android-sdk-brief-introduction-0000001061991343-V5)

## About HUAWEI Location Kit

Location Kit combines the GNSS, Wi-Fi, and base station location functionalities into the apps to build up global positioning capabilities, allowing the developers to provide flexible location-based services for global users. Currently, it provides three main capabilities: fused location, activity identification, and geofence. You can call one or more of these capabilities as needed. To discover more, visit: [Huawei Location Kit Guide](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/introduction-0000001050706106)

## About HUAWEI Site Kit

With Site Kit, applications can provide users with convenient and secure access to diverse, place-related services, and therefore acquire more users. To discover more, visit: [Huawei Site Kit Guide](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/android-sdk-introduction-0000001050158571)



## About HUAWEI Cloud DB

Cloud DB is a device-cloud synergy database product that provides data synergy management capabilities between the device and cloud, unified data models, and various data management APIs. In addition to ensuring data availability, reliability, consistency, and security, CloudDB enables seamless data synchronization between the device and cloud, and supports offline application operations, helping developers quickly develop device-cloud and multi-device synergy applications. To discover more, visit: [Huawei Cloud DB Guide](https://developer.huawei.com/consumer/en/doc/development/AppGallery-connect-Guides/agc-clouddb-introduction)



## What You Will Need

**Hardware Requirements**

- A computer that can run Android Studio.
- A Huawei Phone for debugging.

**Software Requirements**

- Android SDK package
- Android Studio 3.X-4.X
- HUAWEI HMS Core 4.0.2.300 or later
- JDK version: 1.8.211 or later

## Getting Started

Museum App uses HUAWEI services. In order to use them, you have to [create an app](https://developer.huawei.com/consumer/en/doc/distribution/app/agc-create_app) first. Before getting started, please [sign-up](https://id1.cloud.huawei.com/CAS/portal/userRegister/regbyemail.html?service=https%3A%2F%2Foauth-login1.cloud.huawei.com%2Foauth2%2Fv2%2Flogin%3Faccess_type%3Doffline%26client_id%3D6099200%26display%3Dpage%26flowID%3D6d751ab7-28c0-403c-a7a8-6fc07681a45d%26h%3D1603370512.3540%26lang%3Den-us%26redirect_uri%3Dhttps%3A%2F%2Fdeveloper.huawei.com%2Fconsumer%2Fen%2Flogin%2Fhtml%2FhandleLogin.html%26response_type%3Dcode%26scope%3Dopenid%2Bhttps%3A%2F%2Fwww.huawei.com%2Fauth%2Faccount%2Fcountry%2Bhttps%3A%2F%2Fwww.huawei.com%2Fauth%2Faccount%2Fbase.profile%26v%3D9f7b3af3ae56ae58c5cb23a5c1ff5af7d91720cea9a897be58cff23593e8c1ed&loginUrl=https%3A%2F%2Fid1.cloud.huawei.com%3A443%2FCAS%2Fportal%2FloginAuth.html&clientID=6099200&lang=en-us&display=page&loginChannel=89000060&reqClientType=89) for a HUAWEI developer account.

After creating the application, you need to [generate a signing certificate fingerprint](https://developer.huawei.com/consumer/en/codelab/HMSPreparation/index.html#3). Then you have to set this fingerprint to the application you created in AppGallery Connect.

- Go to "My Projects" in AppGallery Connect.
- Find your project from the project list and click the app on the project card.
- On the Project Setting page, set SHA-256 certificate fingerprint to the SHA-256 fingerprint you've generated.
  ![img](https://communityfile-drcn.op.hicloud.com/FileServer/getFile/cmtyPub/011/111/111/0000000000011111111.20200511174103.08977471998788006824067329965155:50510612082412:2800:6930AD86F3F5AF6B2740EF666A56165E65A37E64FA305A30C5EFB998DA38D409.png?needInitFileName=true?needInitFileName=true?needInitFileName=true?needInitFileName=true)

## Using the Application

- Before you run the app, make sure that you have a working internet connection since the application uses Huawei Mobile Services. Otherwise, the app will display a "no connection" dialog until you turn the internet on.


When you first run the app, a splash screen with the application logo welcomes you and directs you to Home Screen, where the users can see the nearest cafes or markets. The app currently provides methods to sign in such as Huawei ID. 

When the application is opened, a map screen appears. This screen aims to show the markets and cafes near us. It can be selected from the icon on the upper right whether market markers or cafe markers will appear. Markets registered to the system are represented by red markers and cafes by blue markers. Only the products on the registered markers can be viewed. You can also look at the price change charts of the products. And by searching by category or product name from the search icon on the top right, the cheapest product is shown on the map. No login is required for these operations. In order to perform the login process, the Navigation Drawer is opened from the icon in the upper left and login is clicked.

The user can register a marker to the system after logging in. There are two options for Markets, the name of the chain market or the name of the local market. As the prices in cafes are very variable according to the location, such a distinction was not made. Products that are not available in different markets or cafes are directed to the product add page by clicking the "Add Product" button at the bottom of the page of each market or cafe. On the product add page, first of all, it is necessary to add the name of the product and its price. Afterwards, the product adding process is completed by selecting the appropriate categories for the product to be added among the predetermined categories and sub-categories. 

After logging in on the page with the products, the wrong product price can be reported, or if the product price is not up to date, the price can be updated. By adding the product to his favourites, the user can follow the current price in the Favorites section of the Navigation Drawer.

## Screenshots
<img src="/screenshots/Screenshot_20210902_145133_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_153449_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_161337_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_161320_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_161325_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210903_175758_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210903_141004_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_161234_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_161259_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_160433_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210903_180803_com.huawei.app.metelik.jpg" width=200></img>
<img src="/screenshots/Screenshot_20210902_160138_com.huawei.app.metelik.jpg" width=200></img>





## Project Structure

Metelik App is designed with MVVM design pattern.

## Libraries

- Huawei Account Kit
- Authentication Kit
- Huawei Map Kit
- Huawei Location Kit
- Huawei Site Kit
- Huawei Nearby Service
- Huawei Cloud DB
- LiveData
- Kotlin Library
- Lifecycle
- DataBinding
- Navigation
- Glide
- AAChartModel
- GSON
- 

## Contributors

- Basar Aksanli
- Begum Avci

## License

Copyright 2021. Huawei Technologies Co., Ltd. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

```
 http://www.apache.org/licenses/LICENSE-2.0
```

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.