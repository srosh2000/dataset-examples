
# Yelp Academic Dataset JSON to CSV Converter

This repository provides a simple utility to convert Yelp's Academic Dataset from JSON to CSV format. 

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Python 3.x installed on your machine.
- [Yelp Academic Dataset](https://www.yelp.com/dataset/documentation/main) in JSON format

### Usage

To convert the Yelp Academic Dataset from JSON to CSV, follow these steps:

1. **Clone this repository**

2. **Run the conversion script:**

   Use the following command in your terminal:

   ```bash
   python json_to_csv_converter.py yelp_academic_dataset.json
   ```

   Replace `yelp_academic_dataset.json` with the path to the JSON file you want to convert.

3. **Output:**

   The script will generate a CSV file in the same directory with the name `yelp_academic_dataset.csv` (or a name matching your input JSON file).

   ```bash
   # For example:
   yelp_academic_dataset.csv
   ```

### Example

```bash
$ python json_to_csv_converter.py yelp_academic_dataset.json
```

After running the command, your JSON file will be successfully converted to a CSV file.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository and submit a pull request.

