# test2
import pandas as pd

url = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/Capstone_edX/Module%201/survey_results_public_2020.csv"

df = pd.read_csv(url)

mean_age = df["Age"].mean()

print("Mean age:", mean_age)
