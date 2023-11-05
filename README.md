# Get Youtube Subscribers

This project is designed to manage and retrieve subscriber information for a YouTube channel. It is built using Node.js and MongoDB.

## Routes

### GET /subscribers

This route provides an array of all subscribers' details in the database.

### GET /subscribers/names

This route provides an array of all subscribers with only two fields: their names and subscribed channel.

### GET /subscribers/:id

This route provides the details of the subscriber with the given ID.

## Running the Project

To run this project, follow these steps:

1. **Install Node.js and npm:**

   Make sure you have Node.js and npm installed on your system. You can download them from [here](https://nodejs.org/).

2. **Install MongoDB:**

   Install and set up MongoDB on your system. You can download it from [here](https://www.mongodb.com/).

3. **Clone the Repository:**

   Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/mdshadab998998/projectalmabeter.git
   ```

4. **Install Dependencies:**

   Navigate to the project directory and install the required dependencies using npm:

   ```
   cd GetYoutubeSubscribers
   npm install
   ```

5. **Start the Server:**

   Use the following command to start the Node.js server:

   ```
   node app.js
   ```

6. **Access the Routes:**

   You can now access the routes using the provided endpoints:

   - `GET /subscribers` to get all subscribers' details.
   - `GET /subscribers/names` to get subscribers' names and subscribed channels.
   - `GET /subscribers/:id` to get details of a specific subscriber by ID.

## Important Note

Make sure you have a valid MongoDB connection URL configured in the project's configuration files. This is typically found in a file named `config.js` or similar. If it's not present, create one and specify your MongoDB connection details.

For further assistance or issues, please contact the project maintainers.
