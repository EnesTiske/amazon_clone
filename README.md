# amazon_clone_tutorial

## About Me

Hello! I’m Enes Tiske, a third-year Computer Engineering student at Gazi University. I’m passionate about learning and honing my skills in software development, and I believe in hands-on experience. As a student, I enjoy taking on clone projects to learn and practice new technologies, and this Amazon clone is one of my projects aimed at understanding the intricacies of e-commerce platforms.

## Project Overview

This project is an Amazon clone, built with the goal of mimicking the core features of an e-commerce site like Amazon. Through this project, I am exploring various aspects of full-stack development, including frontend design, backend logic, and database integration.

## Features Implemented

- User authentication and authorization
- Product catalog with search and filter functionality
- Product details page with dynamic data rendering
- Shopping cart and checkout process
- Order history and user profile management

## Future Plans

- Implementing a payment gateway simulation
- Adding responsive design for mobile views
- Further optimization and adding new features as I learn more

## Technologies Used

- **Frontend**: Flutter, Provider
- **Backend**: Node.js, Express
- **Database**: MongoDB, Cloudinary

  ## Running Locally

After cloning this repository, navigate to the `flutter-amazon-clone-tutorial` folder. Then, follow these steps to set up the project:

1. **Create MongoDB Project & Cluster**  
   - In your MongoDB dashboard, create a new project and cluster.
   - Click on "Connect" and follow the instructions to obtain your MongoDB URI.
   - Replace the MongoDB URI in `server/index.js` with your own URI.

2. **Set up IP Address**  
   - Open `lib/constants/global_variables.dart` and replace the placeholder with your IP address.

3. **Create Cloudinary Project**  
   - Create a Cloudinary account and project, enabling unsigned operations in the settings.
   - In `lib/features/admin/services/admin_services.dart`, replace `dpubyzvcm` and `vtlwp3yd` with your Cloud Name and Upload Preset, respectively.

4. **Run the App**

**Server Side**
```bash
cd server
npm install
npm run dev  # for continuous development
```

   
**Client Side**
```bash
flutter pub get
open -a simulator  # for iOS Simulator
flutter run
```


## Contact

If you’d like to collaborate or have any feedback, feel free to reach out to me at menes.tiske@gmail.com!
