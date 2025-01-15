# Photo-folio {CRUD} App with Firebase

This project allows users to create albums, upload images with titles, and perform CRUD (Create, Read, Update, Delete) operations on the albums and images. The app is built using React.js and Firebase as the backend.

## Features:
- **Create an Album**: Users can create a new album with a title.
- **Upload Images**: Users can upload images inside the albums with a title for each image.
- **View Albums and Images**: All albums and their images are displayed for easy access.
- **Delete Images**: Users can delete images from the album.
- **User-friendly Interface**: The app is simple to use, designed for ease of interaction with a clean UI.

## Technologies Used:
- **React.js**: Frontend library for building the user interface.
- **Firebase**: Backend for authentication and database storage.
  - Firebase Firestore: For storing album and image data.
  - Firebase Storage: For storing uploaded images.
- **React Router**: For navigating between different pages in the app.

## Setup Instructions:

1. **Clone the repository**:
   ```bash git clone <https://github.com/bharatlal124/Photo-folio-Project>```

2. **Install dependencies**:
    ``` npm install```

3. **Set up Firebase**:
    - Create a Firebase project at Firebase Console.
    - Add your Firebase configuration to the firebase.js file.
    - Enable Firestore and Firebase Storage in the Firebase Console.

4. **Run the project**:
    ``` npm start```

5. ```App should now be running on http://localhost:3000```

## How to Use:
- **Create Album**: Click on the "Create Album" button, enter the title, and your new album will appear.
- **Upload Image**: Inside an album, click on the "Upload Image" button, paste the url of the image, and add a title for it.
- **View Images**: Click on any album to view its images.
- **Delete Image**: Hover over an image and click the "Delete" button to remove it from the album.
- **Update Image**: Hover over an image and click the "Update" button to make any change in the image from the album.

## Screen Shot:

![Screenshot 2025-01-13 172019](https://github.com/user-attachments/assets/4cb453c3-06bd-4d12-a544-761031320673)


![Screenshot 2025-01-13 172030](https://github.com/user-attachments/assets/46cbe593-ac12-4383-8fb3-eb57585d512c)


![Screenshot 2025-01-13 172053](https://github.com/user-attachments/assets/b118ed2c-22ba-4bd1-8c85-6351125dcd55)


![Screenshot 2025-01-13 172102](https://github.com/user-attachments/assets/40bb0fe7-8aca-440c-8da5-1201a812a373)


![Screenshot 2025-01-13 172109](https://github.com/user-attachments/assets/f18dd75d-69e5-4778-8461-fa7263c5522f)
