# findhydrant_hikonecity

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application to find fire hydrants and other water sources in Hikone City, Shiga, Japan, using open data. This project visualizes the locations on an interactive map, making it easy to find the nearest water source for firefighting.

## Demo

**Live Application:** **[https://code4fukui.github.io/findhydrant_hikonecity/](https://code4fukui.github.io/findhydrant_hikonecity/)**


![Screenshot of the findhydrant_hikonecity application](https://code4fukui.github.io/findhydrant_hikonecity/ss.jpg)


## Features

- **Interactive Map:** Displays the locations of fire hydrants and other water sources (e.g., water tanks) on a map of Hikone City.
- **Geolocation:** Automatically centers the map on your current location to show nearby hydrants upon loading.
- **Find Nearest:** A "Nearest" (最寄り) button instantly zooms to the closest water source from your current position.
- **Detailed Information:** Click on any icon to view details such as type, pipe diameter, and address in a popup.
- **Intuitive Icons:** Uses distinct icons to differentiate between fire hydrants, water tanks, and other water sources.
- **Easy Navigation:** Use "Previous" and "Next" buttons to cycle through the nearest hydrants in the list.

## How to Run Locally

1.  Clone this repository:
    ```bash
    git clone https://github.com/code4fukui/findhydrant_hikonecity.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd findhydrant_hikonecity
    ```
3.  Open the `index.html` file in your web browser.

## Data Source

This project uses a processed CSV version of the fire hydrant open data from Hikone City.

-   **Source:** 彦根市 消火栓水利データ (Hikone City Fire Hydrant and Water Source Data)
-   **Provider:** Hikone City, Shiga Prefecture
-   **Data URL:** [https://data.bodik.jp/dataset/252026_shoukasen_20200401/resource/88ae56c2-504e-41f9-92d3-ff1175e8d94e](https://data.bodik.jp/dataset/252026_shoukasen_20200401/resource/88ae56c2-504e-41f9-92d3-ff1175e8d94e)

The data is stored locally in the repository as `syoukasen_20200401.csv`.

## Dependencies

This