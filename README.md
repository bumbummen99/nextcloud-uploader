# NextCloud Uploader
Simply upload files to NextCloud using GitHub Actions.

## Information
- [Only up to ~14GB file size supported](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners#supported-runners-and-hardware-resources).
- You **HAVE** to create the directory `/GitHub-Uploads` in the root of your NextCloud.

## How?
1. Go to your NextCloud and create the directory `/GitHub-Uploads`.
2. Fork the repository
2. Configure the following **secrets** for your actions on the forked repository:
   - **NEXTCLOUD_URL:** The base URL of your NextCloud instance- **WITHOUT** trailing slash! 
   - **NEXTCLOUD_USERNAME:** The log in username for your NextCloud account
   - **NEXTCLOUD_PASSWORD:** The (app-)password of the NextCloud account.
3. Run the *Upload* action with your desired inputs and enjoy :)

## Bugs / Contributing
Feel free to report issues or contribute improvements.
