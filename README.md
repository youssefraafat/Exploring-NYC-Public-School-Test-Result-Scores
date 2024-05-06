# NYC Schools SAT Performance Analysis

## Welcome to NYC Schools SAT Performance Analysis!

This repository hosts an insightful Python script tailored to unravel the intricacies of SAT performance among New York City's schools. Our endeavor is to not only identify top-performing institutions but also provide a comprehensive understanding of the educational landscape across different boroughs.

## Dependencies
Ensure a smooth experience by having the following dependencies installed:
- Python 3.x
- pandas

## Dataset
For seamless analysis, procure the dataset named `schools.csv`, featuring essential columns such as:
- `school_name`: Unique identifier for each school.
- `average_math`: SAT math scores averaged per school.
- `average_reading`: SAT reading scores averaged per school.
- `average_writing`: SAT writing scores averaged per school.
- `borough`: The borough where each school is situated.

Simply place this dataset in the root directory of the project.

## Usage

1. Initiate the analysis by depositing the `schools.csv` data file in the project's root directory.
2. Execute the script. Upon execution, the script will:
   - Extract and process data from the provided CSV file.
   - Identify schools with remarkable math performance.
   - Compute the total SAT score for each school.
   - Uncover the top 10 performing schools based on total SAT scores.
   - Reveal the borough showcasing the most diverse performance range in total SAT scores.
3. Delve into the results and gain valuable insights.

## Analysis Results

- `best_math_schools`: A meticulously sorted DataFrame spotlighting schools with an average math score of 640 or higher.
- `top_10_schools`: A curated DataFrame showcasing the top 10 schools based on mean total SAT scores.
- `largest_std_dev`: A revealing DataFrame shedding light on the borough with the most significant standard deviation for total SAT scores.

## Future Enhancements

To enrich our insights further, we envision implementing the following enhancements:
- Expanding the analysis to encompass additional performance metrics like graduation rates or college acceptance rates.
- Harnessing advanced data visualization techniques such as interactive graphs and insightful charts for a more immersive understanding.
- Seamlessly integrating with a robust database system for enhanced data management and accessibility.

## Contributing

Excited about contributing? Fork the repository, enrich it with your enhancements, and submit a pull request. We eagerly await your valuable contributions!

## License

This project is licensed under the MIT License. Feel free to explore, modify, and adapt it according to your needs.
