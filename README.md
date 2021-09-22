# Gopher Chat
This is a simple chat application that is utilizing Go on the backend for it's speed and concurrency features. React is the frontend side.
I plan on adding a few more features to this application such as:
    - User Authentication
    - Avatars
    - Colored messages for a who's who in the chat log
    - CI/CD pipeline and tests

This project is open source and freely available for anyone to clone and use in their own organization or friends circle. 

Please feel free to fork this repo and add features. I will approve Pull Requests as long as they pass any checks in place. 

Instructions for running:
1. Clone or Fork then clone the repo
2. Open up two terminal tabs or instances
3. Navigate to backend directory
4. Run `bash go run main.go`
5. On the second tab navigate to frontend directory
6. If yarn is installed run `bash yarn start`
7. If you don't have Yarn you can install it by running `bash npm i -g yarn`
8. Or if you don't want to use yarn first remove the yarn.lock file
9. Then run `bash npm i`
10. Then `bash npm start`