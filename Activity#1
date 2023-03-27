#Fill in the blanks activity

#-------------------------------------------------------------------------------------------------------------
#This function returns the percentage of busy days for a specific day of the week

def predictDayBusy(array, day):
	numberOfBusy = 0
	numberOfTotal = 0
	for row in array:
			if row[0] == day:
			numberOfTotal = numberOfTotal + 1
			if row[2] == "Yes":
		 		numberOfBusy = _________ + 1

	return numberOfBusy / __________ * 100
	
#-------------------------------------------------------------------------------------------------------------
#This function returns the percentage of busy days for a specific temperature

def predictTempBusy(array, temperature):
	numberOfBusy = 0
	numberOfTotal = 0
	for row in array:
		if row[1] == temperature:
			numberOfTotal = __________ + 1
			if row[2] == "___":
		 		numberOfBusy = numberOfBusy + 1

	return numberOfBusy / numberOfTotal * 100
	
#-------------------------------------------------------------------------------------------------------------
#This function returns the percentage of busy days given a specific day of the week and temperature

def predictBusy(array, day, temperature):
	return (_________(array, day) + _________(array, temperature)) / 2
	
#-------------------------------------------------------------------------------------------------------------

f = open("data.csv", "r")

array = []

for line in f:
	combo = line.strip().split(',')
	array.append(combo)
	
#-------------------------------------------------------------------------------------------------------------

#EXAMPLE:

_____(_________(array, "Friday", "Very Hot"))
