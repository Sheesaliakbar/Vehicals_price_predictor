🚗 Car Price Predictor
Yeh ek Machine Learning project hai jo car ki mukhtalif khoobiyon (factors) jaise ki model, engine type, aur mileage ke basis par uski price predict karta hai.

📋 Project Overview
Is project ka maqsad car ki selling price ka andaza lagana hai. Ismein data ko analyze karne ke liye Exploratory Data Analysis (EDA) ka istemal kiya gaya hai aur prediction ke liye Linear Regression model ka use kiya gaya hai.

🛠️ Tech Stack & Libraries
Is project mein niche di gayi Python libraries ka istemal kiya gaya hai:

Pandas: Data manipulation aur analysis ke liye.

Matplotlib & Seaborn: Data visualization ke liye.

Scikit-learn: Machine Learning model building, splitting aur evaluation ke liye.

📊 Dataset Details
Dataset mein cars ki mukhtalif details shamil hain, jaise:

Car Name: Car ka naam.

Year: Car ka model saal.

Present Price: Car ki mojuda showroom price.

Kms Driven: Car kitni chali hui hai.

Fuel Type: Petrol, Diesel ya CNG.

Seller Type: Dealer ya Individual.

Transmission: Manual ya Automatic.

🚀 Workflow
Data Loading: car_data.csv file ko pandas ke zariye load kiya gaya.

Data Exploration: Dataset ki shape, statistical values aur missing values ko check kiya gaya.

Data Encoding: Categorical data (Fuel Type, Seller Type, Transmission) ko numerical values mein convert kiya gaya taake model behtar samajh sake.

Data Splitting: Data ko Training aur Testing sets mein divide kiya gaya (90% training, 10% testing).

Model Training: Linear Regression model ka istemal karke model ko train kiya gaya.

📈 Results
Model ki performance ko evaluate karne ke liye R-squared error aur metrics ka istemal kiya gaya hai taake prediction ki accuracy ka pata lag sake.
