<img src="./readme/Titles/title1.svg"/>
<br><br>
<img src="./readme/Titles/title2.svg"/>

> An IoT-integrated platform for farmers, flower enthusiasts, and administrators, enabling remote greenhouse management, real-time monitoring, and a seamless flower marketplace experience.
>
> Pétale aims to empower farmers with advanced tools for managing their crops while offering users a convenient way to explore, identify, and purchase flowers. By combining IoT technology, machine learning, and e-commerce, we strive to bridge the gap between technology and nature.

## User Stories

### Gardener
- As a gardener, I want to monitor real-time sensor data (e.g., soil moisture, humidity, temperature), so I can manage my greenhouse remotely and efficiently.

- As a gardener, I want to post my harvested plants on the marketplace, so I can sell them to users conveniently.

- As a gardener, I want to be able to water my crops with a click of a button or through a schedule, so I can be away with a clear mind.

### User
- As a user, I want to upload a picture of a flower, so I can identify its name using the app’s machine-learning feature.

- As a user, I want to browse the flower marketplace, so I can explore and purchase flowers from farmers directly.

- As a user, I want to filter plants and flowers by name, type, or price, so I can find exactly what I need quickly.

### Admin
- As an admin, I want to manage users and oversee marketplace activity, so I can ensure smooth operations and compliance.

- As an admin, I want to ban users and gardeners who violate community guidelines, so I can maintain a safe and respectful environment. 

- As an admin, I want to edit or remove inappropriate content, such as offensive comments or images, so I can maintain the platform's quality.

<br><br>
<img src="./readme/Titles/title3.svg"/>

### Core Technologies

- [React.js](https://react.dev/learn): Powers the frontend interface, providing a dynamic and responsive user experience.
- [Node.js with Express](https://expressjs.com/): Handles server-side operations and REST API endpoints.
- [MongoDB](https://www.mongodb.com/docs/): Primary database for storing application data and user information.
- [Socket.IO](https://socket.io/docs/): Enables real-time communication between the web application and IoT devices.

### Frontend Technologies

- [Material-UI (MUI)](https://mui.com/material-ui/getting-started/overview/): Provides pre-built React components for a polished user interface.
- [Redux](https://redux.js.org/): Manages global state and data flow across the application.
- [ImageKit](https://docs.imagekit.io/): Handles image upload, storage, and optimization.
- [TensorFlow.js](https://www.tensorflow.org/js): Enables client-side flower recognition using a CNN model.

### Machine Learning

- [Python](https://docs.python.org/3/): Used for training the Convolutional Neural Network (CNN) model for flower recognition.
- [TensorFlow](https://www.tensorflow.org/): Framework for developing and training the machine learning model.
- **CNN Architecture**: Implements deep learning for accurate flower classification.

### Hardware Integration

- [C++](https://en.cppreference.com/w/): Programs the microcontroller and handles sensor logic.
- [ESP8266](https://www.espressif.com/en/products/socs/esp8266): WiFi-enabled microcontroller for IoT functionality.

#### Sensors

- [DHT11](https://learn.adafruit.com/dht): Measures temperature and humidity.
- [Soil Moisture Sensor](https://projecthub.arduino.cc/Aswinth/soil-moisture-sensor-with-arduino-91c818): Monitors plant hydration levels.
- [Arduino IDE](https://www.arduino.cc/en/software): Development environment for hardware programming.

### Arduino Libraries

- [ESP8266WiFi](https://arduino-esp8266.readthedocs.io/en/latest/): Manages WiFi connectivity.
- [WebSocketsClient](https://github.com/Links2004/arduinoWebSockets): Handles real-time communication.
- [DHT](https://github.com/adafruit/DHT-sensor-library): Interfaces with temperature/humidity sensor.
- [ArduinoJson](https://arduinojson.org/): Processes JSON data for device communication.

<br><br>
<img src="./readme/Titles/title4.svg"/>

- Project Figma design [Figma](https://www.figma.com/design/ilLm7kQiZ1PIAdFdLGMCpb/Final-Project-Design?node-id=0-1&t=lJnTlvopzHzmWgw3-1)

| Home screen                                   | Menu Screen                                |
| --------------------------------------------- | ------------------------------------------ |
| ![Landing](./readme/assets/GuestHomePage.gif) | ![fsdaf](./readme/assets/UserHomePage.gif) |

<br><br>
<img src="./readme/Titles/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies:

<!-- <img src="./readme/code.png" /> -->

<br><br>
<img src="./readme/Titles/title6.svg"/>

### User Screens

| **Role Screen**                                 | **Sign Up Screen**                              |
| ----------------------------------------------- | ----------------------------------------------- |
| ![Role Selection](./readme/assets/RolePage.jpg) | ![User Sign Up](./readme/assets/SignUpUser.jpg) |

| **User Home Page**                                  | **Marketplace Screen**                          |
| --------------------------------------------------- | ----------------------------------------------- |
| ![User Home Page](./readme/assets/UserHomePage.gif) | ![Marketplace](./readme/assets/Marketplace.jpg) |

| **Plant Post Details**                                      | **Shopping Cart**                                  |
| ----------------------------------------------------------- | -------------------------------------------------- |
| ![Plant Post Details](./readme/assets/PlantPostDetails.jpg) | ![Shopping Cart](./readme/assets/ShoppingCart.jpg) |

| **Checkout**                              | **Orders**                                |
| ----------------------------------------- | ----------------------------------------- |
| ![Checkout](./readme/assets/Checkout.jpg) | ![Orders](./readme/assets/UserOrders.jpg) |

| **Flower Recognition**                                      |
| ----------------------------------------------------------- |
| ![Flower Recognition](./readme/assets/FlowerRecogntion.gif) |

---

### Gardener Screens

| **Gardener Sign Up**                                    | **Growing Plants**                                   |
| ------------------------------------------------------- | ---------------------------------------------------- |
| ![Gardener Sign Up](./readme/assets/SignUpGardener.jpg) | ![Growing Plants](./readme/assets/GrowingPlants.jpg) |

| **Posted Plants**                                  | **Sold Plants**                                |
| -------------------------------------------------- | ---------------------------------------------- |
| ![Posted Plants](./readme/assets/PostedPlants.gif) | ![Sold Plants](./readme/assets/SoldPlants.jpg) |

| **Posted Plant Details**                          | **Gardener Orders**                           |
| ------------------------------------------------- | --------------------------------------------- |
| ![Posted Plant](./readme/assets/PlantDetails.jpg) | ![Orders](./readme/assets/GardenerOrders.jpg) |

| **Growing Plant (unharvested)**                            | **Post Plant Form (harvested)**                 |
| ---------------------------------------------------------- | ----------------------------------------------- |
| ![Growing Plant](./readme/assets/GardenerGrowingPlant.gif) | ![Post Form](./readme/assets/PostPlantForm.jpg) |

### Admin Screens

| **Admin Dashboard**                                    | **Users**                                |
| ------------------------------------------------------ | ---------------------------------------- |
| ![Admin Dashboard](./readme/assets/AdminDashboard.gif) | ![Users](./readme/assets/AdminUsers.jpg) |

| **Gardener Details**                                     | **User Details**                          |
| -------------------------------------------------------- | ----------------------------------------- |
| ![Gardener Details](./readme/assets/GardenerDetails.gif) | ![Users](./readme/assets/UserDetails.png) |

| **Growing Plants**                                        | **Orders**                                |
| --------------------------------------------------------- | ----------------------------------------- |
| ![Growing Plants](./readme/assets/AdminGrowingPlants.png) | ![Users](./readme/assets/AdminOrders.png) |

| **Plant Details**                                       | **Growing Plants**                                       |
| ------------------------------------------------------- | -------------------------------------------------------- |
| ![Plant Details](./readme/assets/AdminPlantDetails.png) | ![Growing Plants](./readme/assets/AdminGrowingPlant.gif) |

<br><br>
<img src="./readme/Titles/title10.svg"/>

This is an example of how to list things you need to use the software and how to install them.

#### Frontend

1. Clone the repo
   ```sh
   git clone https://github.com/mayaeyd/Petale-app.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

#### Backend

1. Get a free API Key at [ImageKit](https://imagekit.io/)
2. Clone the repo
   ```sh
   git clone https://github.com/mayaeyd/Petale-server.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Copy `.env.example` to `.env`
5. Update the values in `.env` with your own credentials

#### Machine Learning

1. Clone the repo
   ```sh
   git clone https://github.com/mayaeyd/Petale-ML.git
   ```
2. Navigate to `flower_project`
   ```sh
   cd flower_project
   ```
3. Run the server
   ```sh
   python manage.py runserver
   ```

