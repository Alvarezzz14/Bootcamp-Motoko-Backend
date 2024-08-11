# `Backend Red Social Simple`

Install following packages:

IC SDK
NVM (optional)
NodeJs
NPM
Git

- [Quick Start](https://internetcomputer.org/docs/current/developer-docs/setup/deploy-locally)
- [SDK Developer Tools](https://internetcomputer.org/docs/current/developer-docs/setup/install)
- [Motoko Programming Language Guide](https://internetcomputer.org/docs/current/motoko/main/motoko)
- [Motoko Language Quick Reference](https://internetcomputer.org/docs/current/motoko/main/language-manual)

## Running the project locally

If you want to test your project locally, you can use the following commands:

# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://localhost:4943?canisterId={asset_canister_id}`.
```
### Funcionalities with console or Candid UI

- whoAmI
- Create Profile (only Authenticated user with Iinternet Identity can create profile)
- Edit Profile 
- Get My Profile
- Get All Profiles
- Create Post
- Edit Post
- Delete Post
- Get My Posts
- Get All Posts
- Create Comments on my posts
- Create create comments on posts of profiles that I follow (only profiles that are followed)
- Get Comments (with id post)
- Send Follow Request (with principal other profile)
- Accept Follow Request (with my pricipal)
- Get Followees Posts
- Get Followers
