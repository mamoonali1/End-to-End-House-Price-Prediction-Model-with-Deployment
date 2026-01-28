### Boston House Pricing Prediction

Features of Boston Dataset :
   - CRIM: Per capita crime rate by town
   - ZN: Proportion of residential land zoned for lots
   - INDUS: Proportion of non-retail business acres
   - CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
   - NOX: Nitric oxides concentration
   - RM: Average number of rooms per dwelling
   - AGE: Proportion of owner-occupied units built prior to 1940
   - DIS: Weighted distances to employment centers
   - RAD: Index of accessibility to radial highways
   - TAX: Property tax rate
   - PTRATIO: Pupil-teacher ratio
   - B: Proportion of Black residents
   - LSTAT: Percentage of lower status population

**Software And Tools Requirements** 
[Github Account](https://github.com)
[VSCodeIDE](https://code visualstudio.com/)
[GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

1. **Create a new environment**
conda create -p venv python==3.10 -y

2. **Install dependencies**
pip install -r requirements.txt

4. **Run the application**
python app.py

5. **Access the application**
Open your browser and navigate to `http://localhost:5000`


### Docker Deployment

1. **Build the Docker image**
docker build -t boston-house-price-prediction .

2. **Run the container**
docker run -p 5000:5000 boston-house-price-prediction

3. **Start the application**
docker-compose up -d

4. **Stop the application**
docker-compose down

