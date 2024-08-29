# Cryptocurrency Tracker App

This is an Android application that fetches and displays real-time cryptocurrency data using the CoinMarketCap API. The app allows users to search for specific cryptocurrencies with real-time suggestions.

## Features

- **Real-Time Cryptocurrency Data**: Fetches the latest cryptocurrency data from the CoinMarketCap API.
- **Search Functionality**: Users can search for cryptocurrencies by name, and the app provides suggestions as they type.
- **RecyclerView**: Displays the cryptocurrency data in a scrollable list with name, symbol, and current price.
- **Edge-to-Edge UI**: The app supports edge-to-edge UI design for an immersive experience.
- **Error Handling**: Displays appropriate messages for empty search results and network errors.

## Screenshots

![Screenshot_20240829_215427](https://github.com/user-attachments/assets/0026edd3-dc12-426c-b976-3ab114f6e5ef)

![Screenshot_20240829_215454](https://github.com/user-attachments/assets/0a5bc852-fa23-4afa-addb-4d77992d3553)


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cryptocurrency-tracker-app.git
    ```
2. Open the project in Android Studio.
3. Add your [CoinMarketCap API Key](https://pro.coinmarketcap.com/signup) in the `MainActivity.kt` file:
    ```kotlin
    headers["X-CMC_PRO_API_KEY"] = "your_api_key_here"
    ```
4. Build and run the app on an Android device or emulator.

## Dependencies

This project uses the following dependencies:

- **AndroidX**: Core libraries for modern Android development.
- **Volley**: HTTP library for making network requests.
- **ViewBinding**: Simplifies interactions with UI components.
- **RecyclerView**: For displaying lists in the app.

Make sure to sync the project with Gradle files to download these dependencies.

## Usage

- **View Cryptocurrency Data**: The main screen lists all available cryptocurrencies with their name, symbol, and current price.
- **Search**: Type in the search bar to filter cryptocurrencies by name.

## API Integration

The app uses the [CoinMarketCap API](https://coinmarketcap.com/api/) to fetch cryptocurrency data. Ensure you have a valid API key and add it to the `MainActivity.kt` file as described in the Installation section.

## Contributing

Contributions are welcome! Please create a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
