# Promtopia - A Creative Writing Community

[DEMO](https://promtopia-eight.vercel.app/)

##### Promtopia is a web application that allows users to participate in a creative writing community. Users can create, update, and delete their writing prompts, fostering a collaborative environment for writers to share their imaginative ideas. Authenticated users can access additional features, while non-authenticated users are limited to reading and searching prompts.


## Table of Contents
- Features
- Getting Started
- Usage
- Contributing
- License

## Features

### User Authentication
- Google Sign-In: Users can log in to Promtopia using their Google accounts, ensuring a secure and convenient authentication process.

### Writing Prompts

- Create Prompts: Authenticated users can create new writing prompts, sharing their creative ideas with the community.
- Update Prompts: Users can edit and update their existing prompts to refine their content.
- Delete Prompts: Authenticated users can delete prompts they no longer wish to keep on the platform.
 
### Reading and Searching

- Read Prompts: Non-authenticated users and authenticated users can freely read and explore the collection of writing prompts.
- Search Prompts: Users can search for specific prompts using keywords, making it easy to find prompts that align with their interests.

## Getting Started

#### Follow these steps to set up and run Promtopia locally on your machine:

```sh
git clone https://github.com/Vasyl-Pavlenko/promtopia.git
cd promtopia
```

#### Install Dependencies:

```sh
npm install
# or
yarn install
```

#### Environment Variables:

```sh
GOOGLE_CLIENT_ID=your-google-client-id
NEXTAUTH_URL=http://localhost:3000
```
 Replace your-google-client-id with your actual Google OAuth client ID.

#### Run the Application:

```sh
npm run dev
# or
yarn dev
```

The application should now be running locally at http://localhost:3000

## Usage
### Sign In:

- Click the "Sign In" button and choose the Google Sign-In option.
- Authenticate with your Google account.

### Create a Prompt:

- Once authenticated, you can create a new writing prompt by clicking the "Create Prompt" button.
- Fill in the details for your prompt, including the title and content.
- Click "Create" to add your prompt to the platform.

### Update and Delete Prompts:

- To edit a prompt you've created, navigate to the prompt and click the "Edit" button.
- To delete a prompt, click the "Delete" button (Note: Deleting is irreversible).

### Read and Search Prompts:

- Even without signing in, users can freely browse and read all available prompts.
- Use the search bar to find specific prompts by keywords or topics.

### Contributing
We welcome contributions to Promtopia. If you'd like to contribute, please follow these steps:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes and ensure the code lints successfully.
3. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
