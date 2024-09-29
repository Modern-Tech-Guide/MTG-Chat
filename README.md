# MTG-Chat

A Simple, real-time chat application built with JavaScript & Firebase.

## Features

- **Real-time messaging**: Instantly send and receive messages between site users
- **User authentication**: You must add in your own
- **Profile pictures**: User Profile Pictures are fetched from firebase storage (Path: profile-pictures/${userid}
- **Message formatting**: Support for links and image embedding in messages (image embedding works so as long as the link is formatted e.g. https://cdn.example.com/photo.png)
- **Timestamps**: See when messages were sent with formatted timestamps
- **Message management**: Delete your own messages
- **Reply functionality**: Easily reply to specific messages
- **Dark mode**: Toggle between light and dark themes for comfortable viewing
- **Responsive design**: Works seamlessly on desktop and mobile devices
- **Persistent theme**: User's theme preference is saved locally

## Technical Highlights

- Built with vanilla JavaScript for frontend
- Firebase Realtime Database for real-time data synchronization
- Firebase Authentication for user management
- Firestore integration for additional data storage capabilities
- Custom CSS for sleek, modern UI design

## Getting Started

1. Clone the repository
2. Set up a Firebase project and update the configuration & paths in `chatcode.js`
3. Open `index.html` in a web browser or deploy to your preferred hosting service

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
