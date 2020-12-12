This is a wrapper for mmconnect Nightscout plugin, to make it possible running it on your computer. 


# Install
0. On your running Nightscout setup remove the `mmconnect` from `ENABLE` variable (disables the mmconnect)
1. Install Node.js
2. Clone this repo to a folder
3. Rename `.env.example` to `.env` and set the values (Environment variables can be used instead of .env file, like in Nightscout. The names are the same as in the .env.example file.)
4. In that folder run `npm install`
5. In that folder run `node run.js`

# Update
For update use the `npm update` command in the folder, because if there are fixes, they are in the dependency.

# Disclaimer
This project is intended for educational and informational purposes only. It relies on a series of fragile components and assumptions, any of which may break at any time. It is not FDA approved and should not be used to make medical decisions. It is neither affiliated with nor endorsed by Medtronic, and may violate their Terms of Service.