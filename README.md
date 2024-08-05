# Consume-API-coinmarketcap-Rust

# Crypto Data Fetcher

This project retrieves cryptocurrency data from the CoinMarketCap API using Rust. It demonstrates how to make a request to the API, parse the response, and print out specific information.

## Setup

### Requirements

- Rust programming language
- `reqwest` and `serde` crates for making HTTP requests and parsing JSON data.

### Configuration

Before running the project, you need to configure it with your own CoinMarketCap API key and update the base URL.

1. **Replace API Key:**

   In the code, locate the `API_KEY` constant and replace its value with your own CoinMarketCap API key. This key is required to authenticate your requests.

   ```rust
   const API_KEY: &str = "your_api_key_here"; // Replace with your CoinMarketCap API key
   ```
2. **Update Base URL:**
Update the BASE_URL constant to use the official CoinMarketCap API URL instead of the sandbox URL. 
   ```rust
   const BASE_URL: &str = "pro-api.coinmarketcap.com";
   ```

# Running the project

1. Clone the repository
   ```bash
   git clone https://github.com/talespalma/cripto_api_cryptocurrency.git
   ```

2. Navigate to the project directory
   ```bash
   cd cripto_api_cryptocurrency
   ```
3. Run the command

   ```bash
   cargo run
   ```
   
