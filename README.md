
# 🦄 My Little Pony · Parquet Magic Reader ✨

A whimsical, privacy-focused, and high-performance **Parquet file visualizer** built with DuckDB-Wasm and themed with the magic of friendship\!

## 🌟 Live Demo

Visit the magical portal here: **[parquet.labmattercounter.top](parquet.labmattercounter.top)**

-----

## 💖 Why "Magic"?

Most Parquet viewers are boring and gray. This tool brings **Equestria's vibrance** to your data engineering workflow. Whether you are analyzing big data or just checking a schema, do it with style\!

### ✨ Key Features

  * **Zero-Server Privacy**: Your data **never leaves your browser**. All processing is done locally via WebAssembly.
  * **Lightning Fast**: Powered by **DuckDB-Wasm**, allowing you to run analytical queries on Parquet files directly in the browser.
  * **MLP Aesthetic**: A custom UI featuring dreamy gradients, cute typography, and magical decorations.
  * **Pagination & Metadata**: Easily browse through large datasets with built-in row and column counters.

-----

## 🛠️ How It Works

This project is a **serverless static web application**. When you upload a file:

1.  **DuckDB-Wasm** initializes a virtual database in your browser's memory.
2.  The `.parquet` file is registered as a local buffer.
3.  SQL queries are executed locally to fetch and display your data.

-----

## 🚀 Deployment

This site is hosted on **GitHub Pages** using a custom subdomain.

### Local Development

To run this locally, simply clone the repository and open `index.html` in a modern web browser:

```bash
git clone https://github.com/balabalabalalaba/your-repo-name.git
cd your-repo-name
# You can use a simple live server to view it
npx serve .
```

-----

## 📂 Project Structure

  * `index.html`: The magical core (HTML5, CSS3, and JavaScript).
  * `mlp_background.png`: The dreamy backdrop for your data journey.
  * `README.md`: You are here\!

-----

## 🛡️ Privacy & Security

We believe that **Friendship is Magic, and Privacy is Paramount**.

  * **No Telemetry**: We don't track what you upload.
  * **No Backend**: There is no database or server storing your files.
  * **Offline Ready**: Once the page is loaded, you can turn off your internet and it will still work\!

-----

## 🌈 Acknowledgments

  * **DuckDB Team** for the incredible [DuckDB-Wasm](https://github.com/duckdb/duckdb-wasm) engine.
  * **Google Fonts** for the cute typography.
  * The MLP Fandom for the inspiration.

-----

> *"The magic of data is even stronger when shared with friends\!"* 🦄📊
