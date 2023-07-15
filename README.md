# Vehicle List

This is a Java class vehicleList that provides functionalities for managing a collection of vehicles. It uses an ArrayList to store the vehicles and provides methods for adding vehicles, reading vehicle data from a file, printing the list, and performing calculations on the vehicle data
## Class Methods
### public void addVehicle(vehicle v)
This method adds a vehicle object to the vehicle list.

### public void readInFile(String fileName)
This method reads data from a file and creates a vehicle object for each line in the file. The file should be in comma-separated values (CSV) format with the following fields: make, model, year, mileage, price, type, color, and emission. The method takes a fileName parameter specifying the name of the file to be read.

### public void printList()
This method prints each vehicle object in the list on a new line. It uses the toString() method of the vehicle class to display the vehicle information.

### public vehicle highestEmissions()
This method returns the vehicle with the highest emissions from the list. It iterates over the vehicles in the list and compares their emissions to find the vehicle with the highest value.

### public vehicle lowestEmissions()
This method returns the vehicle with the lowest emissions from the list. It iterates over the vehicles in the list and compares their emissions to find the vehicle with the lowest value.

### public double meanEmissions(String type)
This method calculates and returns the mean emissions for a given type of vehicle. It takes a type parameter specifying the vehicle type for which the mean emissions should be calculated. It iterates over the vehicles in the list, filters them by the specified type, and calculates the mean emissions by summing up the emissions and dividing by the number of vehicles of that type.

# Usage
Create an instance of the vehicleList class: vehicleList list = new vehicleList();
Add vehicles to the list using the addVehicle() method: list.addVehicle(vehicleObject);
Read vehicle data from a file using the readInFile() method: list.readInFile("filename.txt");
Print the list of vehicles using the printList() method: list.printList();
Retrieve the vehicle with the highest emissions using the highestEmissions() method: vehicle highest = list.highestEmissions();
Retrieve the vehicle with the lowest emissions using the lowestEmissions() method: vehicle lowest = list.lowestEmissions();
Calculate the mean emissions for a specific vehicle type using the meanEmissions() method: double mean = list.meanEmissions("type");
Note: Replace vehicleObject with an instance of the vehicle class and "filename.txt" with the name of the file containing the vehicle data.

Make sure to import the necessary libraries and ensure that the vehicle class is defined with the required fields and methods used in this class.




