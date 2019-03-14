After [installing](../installation.md) bunqDesktop you will need to follow these easy steps to get started:

1. Choose a secure password which is used to encrypt your data.
![Screenshot](../images/setup/1.png)

2. Enter a device name. (This name will be shown in your bunq app)

3. Open the bunq app and go to your Profile -> Security & Settings -> Developer.

3. Click on OAuth at the top. 

4. Here add a redirect URL matching the following value EXACTLY! `http://localhost:1234`

5. Click on `Show client details` and copy the Client ID and Client Secret into bunqDesktop.

6. Click on the authorize button which will open a screen with a QR code.

7. Scan the QR code with the bunq app and give yourself permission.

8. The screen on your desktop should update (You might have to click continue).

9. It should log you in right away as soon as the pop-up screen closes. If the settings are open, there should now be a long text in the API key field and the `Set API key` button should now be clickable
