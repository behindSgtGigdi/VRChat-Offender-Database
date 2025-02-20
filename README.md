# VRChat Predator Reporting System

## Overview
The VRChat Predator Reporting System is a tool designed to help users report suspicious or inappropriate behavior within VRChat. Reports, including user IDs and video proof, are stored in a secure database to keep the community informed and safe.

## How It Works
1. **Submit a Report**: Use the `/report` command in the Discord server to report a user.
2. **Provide Details**: Enter the user's VRChat user ID and a brief description of the incident.
3. **Upload Video Evidence**: You will be given access to a private channel where you can submit video proof.
4. **Verification**: The report is stored in the database and logged in a staff-only channel for review.

## Discord Server
Join our official Discord server for updates, support, and community discussions: [GIGDI Pullers](https://discord.gg/7cyrKZcj8W)

## Commands
- `/report <userid> <description>`: Submit a new report.
- The bot will grant you temporary access to a dedicated report submission channel.

## Report Handling Process
1. The bot ensures a secure MongoDB connection.
2. A dedicated channel is used for report submissions, where only the reporter and staff have access.
3. The submitted video proof is logged and stored in a MongoDB collection.
4. Once the report is submitted, the user’s access to the report channel is revoked.

## Technical Details
- **Database**: MongoDB is used to store reports.
- **Discord Integration**: A bot facilitates the reporting process via interactions.
- **Security**: Users cannot see past reports, ensuring privacy.

## Setup
1. Join Discord:
   ```sh
   https://discord.gg/7cyrKZcj8W
   ```

## License
This project is intended for community safety and ethical reporting. Unauthorized misuse or violations of Discord’s TOS will result in action taken against offending users.
