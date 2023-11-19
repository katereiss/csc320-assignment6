Create an automobile class that will be used by a dealership as a vehicle inventory program. The following attributes should be present in your automobile class:

private string make
private string model
private string color
private int year
private int mileage

Your program should have appropriate methods such as:

default constructor
parameterized constructor
add a new vehicle method
list vehicle information (return string array)
remove a vehicle method
update vehicle attributes method

Start Program

class Automobile
    private String make
    private String model
    private String color
    private int year
    private int mileage
    private int vehicleId

    private ArrayList inventory

    public String addVehicle(String autoMake, String autoModel, String autoColor, int autoYear, int autoMileage, int autoId) 
        Create new Automobile instance
        Add new vehicle to inventory with autoMake, autoModel, autoColor, autoYear, autoMileage, and autoId


    public String listVehicles()
        Create array of strings with size of len(inventory)
        For vehicle in inventory
            Add vehicle information to array as a string
        Return array

    public String RemoveVehicle(String autoMake, String autoModel, String autoColor, int autoYear, int autoId)
        For vehicle in inventory
            If values entered match values stored in private variables
                remove vehicle from inventory
                return "Vehicle removed"
            else 
                return "No matching vehicle found"

    public String updateVehicle(String autoMake, String autoModel, String autoColor, int autoYear, int autoMileage, int autoId)
        For vehicle in inventory
            If autoId matches vehicleId
                replace new value(s) in inventory
                return updated vehicle information
            else 
                return "No matching vehicle found"

End Program
