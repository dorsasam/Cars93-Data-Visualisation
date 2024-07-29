# Cars93 Data Visualization Project
## Project Description
This project showcases data visualizations created using the Seaborn library, based on the [Cars93](https://jse.amstat.org/v1n1/datasets.lock.html) dataset. The dataset contains information on 93 new cars for the 1993 model year, including various measures such as price, mpg ratings, engine size, body size, and feature indicators. With 26 variables, the dataset offers a broad range of statistical techniques typically found in introductory courses.

## Installation
- Clone the repository:
```bash
git clone https://github.com/yourusername/cars93-data-visualization.git
```
- Navigate to the project directory:
```bash
cd cars93-data-visualization
```
- Create a virtual environment and activate it:
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```
- Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Data Description
The Cars93 dataset includes the following variables:

- **Manufacturer**: The manufacturer of the car.
- **Model**: The model of the car.
- **Type**: The type of car.
- **Min.Price, Price, Max.Price**: The minimum, midrange, and maximum price of the car.
- **MPG.city, MPG.highway**: Miles per gallon in city and highway driving.
- **EngineSize**: Size of the engine (in liters).
- **Horsepower**: Horsepower of the engine.
- **RPM**: Revolutions per minute at the maximum horsepower.
- **Rev.per.mile**: Revolutions per mile.
- **Fuel.tank.capacity**: Fuel tank capacity (in gallons).
- **Passengers**: Number of passengers.
- **Length, Wheelbase, Width, Turn.circle, Rear.seat.room, Luggage.room**: Various dimensions of the car.
- **Weight**: Weight of the car (in pounds).
- **Origin**: Country of origin.
- **Make**: Combination of manufacturer and model.

## Visualizations
Four types of plots were used for data visualization purposes:

- Boxplot:

This plot compares car manufacturers based on the revolutions per mile of their vehicles. The primary aim is to evaluate and rank the manufacturers according to this specific feature, determining which manufacturer achieves the highest revolutions per mile.

- Histogram:

This plot compares the miles per gallon (MPG) usage for city and highway driving to determine which is more fuel-efficient.

- Lineplot:

This plot examines the potential correlation between the turning circle and wheelbase by plotting these two variables against each other. 

- Barplot:

This plot compares the average horsepower across different car sizes to determine if larger cars have higher horsepower.

