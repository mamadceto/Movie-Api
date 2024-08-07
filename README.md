# Movie API

Movie API is a simple Node.js application that provides endpoints for retrieving and searching movie data from an external API.

## Features
- Fetch latest movie updates
- Search for movies
- Retrieve detailed information about series
- Get movies by genre

## Endpoints

- `/list`: Fetches the latest updates.
- `/search?text=<query>`: Searches for movies based on the query.
- `/get?id=<id>`: Retrieves series information based on the series ID.
- Genre-specific endpoints:
  - `/MAction`
  - `/MAdventure`
  - `/MAnimation`
  - `/MWeeklyoffer`
  - `/MChinaJapan`
  - `/MComedy`
  - `/MCool`
  - `/MCriminal`
  - `/MDocumentary`
  - `/MWestern`
  - `/MDrama`
  - `/MWar`
  - `/MFamily`
  - `/MFantasy`
  - `/MFavorites`
  - `/MHistorical`
  - `/MIndian`
  - `/MKorean`
  - `/MMusic`
  - `/MMystery`
  - `/MNewseries`
  - `/MOscar2023`
  - `/MRomantic`
  - `/MScary`
  - `/MScienceFiction`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/movie-api.git
    ```

2. Navigate to the project directory:
    ```sh
    cd movie-api
    ```

3. Install dependencies:
    ```sh
    npm install
    ```

4. Start the server:
    ```sh
    npm start
    ```

The server will start on port 3000 by default. You can access it at `http://localhost:8000`.

## Demos

You can use the Endpoints section to test the demo and put what you want at the end of the domain below

- [https://cetomovie.onrender.com/](https://cetomovie.onrender.com/)

### Example :

To fetch movies in the Action genre, you can use the following URL:

- [https://cetomovie.onrender.com/MAction](https://cetomovie.onrender.com/MAction)


## Contact

For any inquiries or feedback, please contact [@mmdceto](https://t.me/mmdceto).
