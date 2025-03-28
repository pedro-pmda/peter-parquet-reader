# 🕷️ Peter Parquet Reader

<p align=center>
  <img src="./logoPeterParquetReader.png" alt="Peter Parquet Reader Logo" width="55%" />
</p>

**Peter Parquet Reader** is a fun and powerful developer tool that lets you preview Parquet file schemas directly in the browser. It uses:

- ⚙️ Go + WebAssembly (WASM)
- 📦 [parquet-go](https://github.com/parquet-go/parquet-go) by Twilio
- 🖼️ Vue 3 for a snappy UI

---

## 🧬 Why?

Parsing Parquet files on the frontend is usually not possible due to their binary structure. But thanks to Go and WebAssembly, Peter Parquet reads them like a superhero — directly in your browser.

---

## 🚀 Features

- 🗂️ Visualize complex Parquet schemas
- 🧠 Uses native Go performance through WebAssembly
- 🧩 Lightweight, embeddable Vue 3 component
- 🕸️ Inspired by Spider-Man, but with data powers

---

## 🛠️ Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/peter-parquet-reader
cd peter-parquet-reader

# Install frontend dependencies
npm install

# Build the WASM module
make wasm

# Run the dev server
npm run dev
```

---

## 🧪 Tech Stack

| Layer   | Tech                                                   |
| ------- | ------------------------------------------------------ |
| UI      | Vue 3                                                  |
| Logic   | Go + WebAssembly                                       |
| Parsing | [parquet-go](https://github.com/parquet-go/parquet-go) |
| Styling | Tailwind (optional)                                    |

---

## 🕸️ About the Name

"Peter Parquet" is a tongue-in-cheek reference to Peter Parker, a.k.a. Spider-Man — just like him, this tool is fast, agile, and reads the web of data.

---

## 📜 License

MIT License
