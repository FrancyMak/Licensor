# Licensor
Licensor is a personal project I created to include any premium features within my bots. This bot allows you to manage licensing and verification of the user who purchased the license.

## Features
- Creation of licenses by specifying the product and duration
- Revocation of licenses and display of expired licenses
- Information about licenses, such as owner, product, creation and expiration date, whether or not it was used, and where it was used.
- Automatic checking of the validity of licenses

## How it works.
The bot is currently in development, so it only has license creation, management, license revocation, license validity checking, and expired license display. In development are the **APIs** for will be integrated into my bots so I don't have to recreate a licensing system every time. 

## Commands
The main commands can only be used by the admin:

### Admin
- `/license create <product> <duration>`: creates a license for the specified product with the specified duration.
- `/license delete <license>`: deletes the specified license.
- `/license info <license>`: shows the specified license information.
- `/license active <license>`: activate the specified license (in development only, API will be used in the future).

### User
- `/verify`: checks if the user has a valid license and provides the role for premium support.

## ToDo.
- [ ] Add API for integration with bots.
- [ ] Add license revocation command.

### Gallery
![image](https://user-images.githubusercontent.com/75610581/227705948-adb86329-aed9-4e60-bddf-5ba4f497065e.png)
![image](https://user-images.githubusercontent.com/75610581/227705959-872a368a-b4d7-43cd-939a-9c117ccef71b.png)
![image](https://user-images.githubusercontent.com/75610581/227705968-275dffe1-2ed7-4d9e-852b-43341e01ab6b.png)
