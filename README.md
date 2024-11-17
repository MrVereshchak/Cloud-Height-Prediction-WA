# Cloud Height Prediction in Washington State 🌥️

**Author**: Darii Vereshchak  
**LinkedIn**: [Darii Vereshchak](https://www.linkedin.com/in/darii-vereshchak/)

This project develops a deep learning model to predict the height of clouds in Washington State. Using **LSTM** and **ConvLSTM** models, the project focuses on accurate 1-hour predictions based on 6-hour historical data.

---

## Dataset
- **Source**: 
  - ERA5 dataset (European Centre for Medium-Range Weather Forecasts): [link](https://rda.ucar.edu/datasets/d633000/)
  - Elevation dataset: [link](http://research.jisao.washington.edu/data_sets/elevation/)
- **Features**: Cloud Base Height, Low Cloud Cover, Wind, Temperature, Precipitation, Elevation, and more.
- **Coverage**: 2018–2023, gridded at 0.25x0.25 degrees (~27x27 km).

---

### Performance
- Best model: **ConvLSTM** with a Mean Absolute Error (MAE) of **818.9 meters**.
- Ongoing improvements with visual evaluation [link](https://www.figma.com/file/Y6lW9LJ9CjJbfnvbfKJUka/Cloud_project?type=design&node-id=0%3A1&mode=design&t=H6qGNtS56ROs9Kmk-1).
