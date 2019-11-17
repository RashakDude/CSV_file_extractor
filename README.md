# CSV_file_extractor
This helps in seperating the data of similar type from a CSV (Comma Seperated Values) file and store the data in a text file. <br>
This is created using python 3.7

## How to use
1. First you need to clone the repository in your local system. To do this just open your terminal and type -<br> 
```
git clone https://github.com/RashakDude/CSV_file_extractor.git
```

2. Then you need to be in the directory of the project. To do this simply type - <br>
```
cd CSV_file_extractor
```

3. Then proceed to the venv folder inside this project using - <br>
```
cd venv
```

4. Now in the <b> C:\Users\User\CSV_file_extractor\venv </b> folder, copy your CSV file.<br>
Now to seperate the similar data just type the following command - 
```
python Coordinator.py -f [name of your file with .csv extension]
```

Just for an instance, I have attached a file named as [sample-csv.csv](/venv/sample-csv.csv)<br>
After implementing the above statements, I was capable of getting different files names with .txt extension. These files were<br>

- [citizenship.txt](/venv/citizenship.txt)
- [country_of_residence.txt](/venv/country_of_residence.txt)
- [direction.txt](/venv/direction.txt)
- [estimate.txt](/venv/estimate.txt)
- [month_of_release.txt](/venv/month_of_release.txt)
- [passenger_type.txt](/venv/passenger_type.txt)
- [standard_error.txt](/venv/standard_error.txt)
- [status.txt](/venv/status.txt)
- [visa.txt](/venv/visa.txt)
- [year_month.txt](/venv/year_month.txt)
