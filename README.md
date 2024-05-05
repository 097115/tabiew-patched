# Tabiew

Tabiew is a lightweight, terminal-based application designed to help view and query CSV files directly in your terminal. It utilizes Polar data frames and its querying engine to perform complex data manipulations without the need for a database system.

![Image Alt text](/images/screenshot.png "Screenshot")

## Features 🌟

- 📊 **Table View**: Explore your data with an easy-to-navigate table view.
- 🔍 **Detailed View**: Dive deeper with a detailed view of individual records to inspect specific data entries.
- 🛠️ **SQL Query Capability**: Utilize SQL for powerful data querying within the app to perform filtering, sorting, and aggregations directly from your terminal.

## Installation

Since Tabiew is in its early stages, it has not been published in any package manager and needs to be built from the source.

First, make sure you have the 1.80.0-nightly version of Rust installed.

```bash
git pull https://github.com/shshemi/tabiew.git
cd tabiew
rustup override set nightly
cargo build --release
cp ./target/release/tabiew <system_or_local_bin_path>
```

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests with your features and bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
