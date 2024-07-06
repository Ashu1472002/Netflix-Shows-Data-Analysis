# Netflix Shows Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis and Visualization](#analysis-and-visualization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview
This project provides an in-depth analysis of Netflix shows using Python and various libraries. The goal is to gain insights into the characteristics and performance of Netflix's content, including ratings metrics, shows distribution, and more.

## Features
- Analysis of Netflix shows and movies
- Rating analysis
- Shows distribution visualization
- Country-specific content analysis
- Top-rated and most-watched shows identification
- Interactive visualizations

## Installation
To get started with the project, follow these steps:

### Using Google Colab
1. **Open the Colab Notebook**: You can run this project directly in Google Colab without any local setup. Open the [Google Colab Notebook](https://colab.research.google.com/drive/1KnAJJJ2IoKelHShueLQtCRZrqgX_QSF3?usp=sharing).
2. **Upload the Dataset**: Ensure you have the `netflix_titles.csv` file uploaded to the Colab environment.

### Local Setup
If you prefer to run the project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Ashu1472002/Netflix-Shows-Data-Analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Netflix-Shows-Data-Analysis
    ```
3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
5. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
6. Download and Place the Dataset:
    - Ensure you have the `netflix_titles.csv` file in the project directory.

## Usage
1. Ensure you have the necessary dataset file (`netflix_titles.csv`) in the project directory.
2. Run the analysis script:
    ```sh
    python analysis.py
    ```
3. Explore the generated visualizations and insights.

## Data
The dataset used in this project is `netflix_titles.csv`, which contains information about Netflix shows and movies, including titles, ratings, type, cast, and more.

## Analysis and Visualization
The project includes various analyses and visualizations such as:
- **Shows Distribution**: Visualization of the distribution of different genres.
- **Ratings Distribution**: Analysis of the highest-rated shows.
- **Movies Vs TV Shows**: Identification of the most-watched shows.
- **Content by Country**: Analysis of content distribution by country.

Example visualizations:
- Movies Vs TV Shows:
    ![image](https://github.com/Ashu1472002/Netflix-Shows-Data-Analysis/assets/71172888/8bcc90d1-a26e-48d1-a66d-b5b89b9af452)


- Content by Country:
   ![image](https://github.com/Ashu1472002/Netflix-Shows-Data-Analysis/assets/71172888/a734d66d-0fcf-4f41-b34f-8e26d96613f8)


   
- Word cloud for Shows-Titles
    ![image](https://github.com/Ashu1472002/Netflix-Shows-Data-Analysis/assets/71172888/ff38ec40-1fd0-445c-976b-bf5c200df91e)



## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please reach out to:
- Your Name: [ashu1472002@gmail.com](mailto:ashu1472002@gmail.com)
- GitHub: [Ashu1472002](https://github.com/Ashu1472002)

---

Happy coding!
