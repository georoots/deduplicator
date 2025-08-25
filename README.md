# GeoRoots Deduplicator
Browser based tool for feature and geometry deduplication for EUDR compatible GeoJSON files

## Usage

* Open the deduplicator.html file in your browser.
* Select a language from the dropdown at the top.
* Drag & Drop correctly prepared .geojson file into the centre of the page or use the file selector button.
* Once loaded, there are two collapsible sections - Conflicting and Non-Conflicting duplicate groups. At the end of the deduplication, only single geometry from each duplicate group will be kept.
* In the conflicting section, you must select single choice of the resulting properties that will be kept. The rest will be discarded
* In the non-conflicting section, choice does not matter, all properties should be identical. The app will automatically only keep one copy of each and discard the rest.
* Once complete, press generate GeoJSON and the final file will be donwloaded by your browser and saved into your downloads.

## FAQ

##### Q: **My language is not included. Can it be added?**
A: Yes, please open an issue ticket and request a new language.

##### Q: **I have many duplicates and want to select all of them based on certain property. Can I do it without having to select them one by one?**
A: Use the app GeoRoots Splitter and split the file by the property you need. If that doesn't get the result you need, try ordering the file first in the Splitter so that the correct duplicate is selected by default in the deduplicator.



## About GeoRoots: Open Source Coffee Industry Tools for EUDR Compliance and geo traceability

GeoRoots is a collection of minimalistic, open-source tools designed specifically for EU Deforestation Regulation (EUDR) requirements and enhancing geo traceability.

Our philosophy is simple: provide useful tools that respect your privacy, work offline (where possible), and require no complex setup or subscription fees. Every tool runs entirely in your browser and can be downloaded for offline use.

### Why Use GeoRoots?

*   **100% Private**: All tools run locally in your browser. No data is ever transmitted to external servers.
*   **Open Source**: Fully open source and transparent. Inspect, modify, and contribute to the code.
*   **Offline Ready**: Download and use tools completely offline. Perfect for remote locations.
*   **Mobile Friendly**: Works on desktop, tablet, and mobile devices.

### Perfect for:

*   Producers and cooperatives
*   Smaller traders and exporters
*   Importers, operators
*   Sustainability consultants

### Useful Official Resources

*   [EUDR DDS on LIVE Environment](https://eudr.webcloud.ec.europa.eu/tracesnt/)
*   [EUDR DDS on TEST Environment](https://acceptance.eudr.webcloud.ec.europa.eu/tracesnt/)
*   [EUDR on Green Forum](https://green-forum.ec.europa.eu/deforestation-regulation-implementation/information-system-deforestation-regulation_en)
*   [EUDR on EUR-Lex](https://eur-lex.europa.eu/legal-content/EN/HIS/?uri=CELEX:52024PC0452)

### License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

### Contributing

We welcome contributions! Please see our [contribution guidelines](CONTRIBUTING.md) for more information.


### Contact

For any questions or feedback, please open an issue on this repository.
