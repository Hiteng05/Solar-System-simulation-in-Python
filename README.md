This Project Simulates the movement of the inner 4 planets of the solar system using newton's equations of motion and real data from Nasa jpl horizons database.

The code uses matplotlib,numpy,astroquery.jplhorizons libraries.
The user can input the exact date of the start and end of the simulation. Data is retrieved from the jpl horizons database regarding the coordinates of the planets on that date.
The user can also change the value of the gravitational constant G , as well as the mass of the sun , in order to the affects in the tragectories of the planets.
The program also provides a label whether Earth would be Habitable or Inhabitable for biological life for the values of G and Sun's mass provided by the user.

The Program also interfaces with MySQL to save all the inputs provided by the user in various test cases , as well as the habitability status obtained in the respective cases.
Thus a robust dataset of testcases can be constructed , which can be used for both research as well as educational purposes.
