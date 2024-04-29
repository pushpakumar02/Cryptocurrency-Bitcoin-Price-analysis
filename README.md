# Google Trends Analysis: Bitcoin Search Volume and Price

## Introduction
This project explores the relationship between the search popularity of Bitcoin on Google Trends and its price. It investigates whether spikes in search volume correlate with changes in Bitcoin's price.

## Data Sources
- Google Trends: Provides search volume data for Bitcoin.
- Yahoo Finance: Provides daily Bitcoin price data.

## Project Structure
- `Bitcoin Search Trend.csv`: Contains Google Trends data for Bitcoin searches.
- `Daily Bitcoin Price.csv`: Contains daily Bitcoin price data.
- `analysis.ipynb`: Jupyter Notebook containing the analysis.
- `README.md`: This file, describing the project.

## Dependencies
- pandas
- matplotlib

## Data Cleaning
- Checked for missing values in both datasets.
- Converted date strings to DateTime objects.
- Resampled daily Bitcoin price data to monthly.

## Data Visualization
- Plotted Bitcoin price against search volume.
- Explored correlations between search volume spikes and price changes.

## Contributing
Contributions to this project are welcome! If you have any suggestions, improvements, or new insights, feel free to open an issue or submit a pull request.

### How to Contribute
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

### Contributors
- [Pushpa Kumar](https://github.com/Pushpakumar02)

## Credits
This project was created as part of Angela Yu's 100 Days of Code course.

## License
This project is licensed under the [MIT License](LICENSE).
