## What is it?
This workflow will automatically restart your EpikHost server whenever you update the Github repository.

## How do I use it?
You can take this workflow.yml and put it in your Github repository inside of a .github/workflows folder. This is required.

After this go to Settings within the repository and then go to secrets and then create a secret with the name of `pterodactyl_panel_api_key` and then you will go to the [panel](https://panel.epikhost.xyz). After this click on API Credentials and then put that as the value.
You will also need to create another secret with the key `server_id` with the value of the last 8 letters of the url for your server. or you can remove the id environment variable and place your it there.
Now the github action should work, to test it out go and push a new change and watch your EpikHost server.

## I found an issue!
Open one.

## I want to contribute!
Thank god, anyways you just should open a pull request.

## It isn't working!
Create an issue.

This workflow *should* work with every langauge!
