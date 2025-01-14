+++
date = '2025-01-13T20:19:32+05:30'
draft = false
title = 'Photo Cloud'
tags = ['SvelteKit', 'PocketBase']
+++


## Introduction

[PhotoCloud](https://sleepyminer.github.io/ImageServer/) is an app which started as a side project to experiment how image hosting website like, [Unsplash](https://unsplash.com/), [ShutterStock](https://www.shutterstock.com/), [Pixabay](https://pixabay.com/) work in the backend to handle the images and different users. So, to explore i went on to create this project and this project was started with new BaaS named [Pocketbase](https://pocketbase.io/) and [SvelteKit](https://svelte.dev/docs/kit/introduction) as the framework for backend.

![Photo-Cloud](/images/Project/ImageServer.png)

## Technologies Used

PhotoCloud leverages a variety of modern web technologies:

- **Svelte (48.2%)**: Our primary framework for building the user interface. Svelte is known for its simplicity and performance.
- **JavaScript (25.8%)**: Used for various functionalities across the application.
- **TypeScript (24.3%)**: Provides type safety and helps maintain large-scale JavaScript codebases.
- **HTML (1.3%)**: The backbone of web content.
- **Other (0.4%)**: Includes various supporting libraries and tools.

## Project Structure

The project is organized into several key components:

1. **Frontend**: Built using Svelte, providing a responsive and interactive user interface.
2. **Backend**: PocketBase handles image uploads, storage, and retrieval as well as authentication and security.
3. **Database**: Pocketbase uses SQlite for storing data and user information.

## Key Features

### Image Upload

Users can upload images seamlessly. The process involves:

1. Selecting an image file.
2. Uploading the file to the server.
3. Storing the file and its metadata in the database.

### Image Hosting

Once uploaded, images can be hosted and shared. The server ensures efficient retrieval and display of images.

### User Authentication

To secure the platform, user authentication is implemented. This includes:

1. User registration.
2. Login and logout functionalities.
3. Session management.


## Conclusion

Building PhotoCloud was an exciting journey. I combined several modern technologies to create a seamless image hosting and uploading experience. I hope this blog post provides insight into my development process and inspires you in your projects.

## Future Plans

I have several features planned for future releases, including:

- Enhanced image editing capabilities.
- Advanced search and filtering options.
- Mobile app integration.

Stay tuned for more updates!



## Get Involved

If you're interested in contributing to PhotoCloud, check out my [GitHub repository](https://github.com/SleepyMiner/ImageServer) for more details.

---

Thank you for reading! If you have any questions or feedback, feel free to leave a comment below.