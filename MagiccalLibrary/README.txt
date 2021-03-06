Magiccal is a Python Library that includes 11 different types of complex calculations that can be now simply used with the help of Magic - Cal(Calculator).
The 11 types of calculations includes :

1. from magiccal import Data
- Digital Data Converter (K, KB, MB, GB, TB, PB) : 
Syntax  : Data.<to be converted data>(<existing value>, <existing data>)
Example : Data.GB(3000,MB)
The following example shall converte the 3000 Mb into GB.

2. from magiccal import BMI
- Body Mass Index Calculation along with the status (Underweight, Normal, Overweight) :
Syntax  : BMI(<height in cms>, <weight in kgs>)
Example : BMI(178, 60)
The following example shall return the BMI for 178 cms height and 60 kgs weight.

3. from magiccal import Discount
- simply input details and get the Discount amount return without any extra calculations.:
Syntax  : Discount(<total amount>, <discount percent>)
Example : Discount(2000, 60)
The following example shall return the Discount on 2000 with 60% of discount on it.

4. from magiccal import Date
- Date helps us to identify the number of days difference between 2 different dates :
Syntax  : Date(<start_date>, <end_date>, <date_format='%d/%m/%Y'>)
Example : Date(25/08/2021, 16/08/2021)
The following example shall return the days difference between the start and the end date.

5. from magiccal import Age
- Age Calculator helps us to identify the age of a person by inserting the Birth Date value :
Syntax  : Age(<dob>, <date_format='%d/%m/%Y'>)
Example : Age('25/08/1990')
The following example shall return the Age of the given date of birth.

6. from magiccal import Time
- Time Converter includes conversion between (Day - D |Week - W | Month - M | Year - Y) :
Syntax  : Time.Day(<existing value>,<existing unit>)
Example : Time.Day(8, 'M')
The following example shall return the number of days from the existing 8 Months.

7. from magiccal import Decimal
- Numeric System Calculator helps us calculate and convert from decimal to its Binary, Octal and Hexadecimal values :
Syntax  : Decimal(<decimal val>)
Example : Decimal(54)
The following example shall return the Binary, Octal and Hexadecimal values of the given decimal.

8. from magiccal import Temperature
- Temperature Converter (C, F, K, R, Re) :
Syntax  : Temperature.C(<existing temperature value>, <existing temperature unit>)
Example : Temperature.C(15, 'K')
The following example shall return the converted temperature for C from 15 K.

9. from magiccal import Speed
- Speed Converter (miles per hour - mph | foot per second - fps | meter per second - mps | kilometer per hour - kmh | knot - kn) :
Syntax  : Speed.mps(<existing Speed value>, <existing Speed unit>)
Example : Speed.mps(200, 'kmh')
The following example shall return the converted Speed for mps from 200 kmh.

10. from magiccal import Pressure
- Pressure Converter (Pascal - Pa | Bar | Pound per square inch - Psi | Standard Atmosphere - atm | Torr) :
Syntax  : Pressure.Pa(<existing Pressure value>, <existing Pressure unit>)
Example : Pressure.Pa(28, 'Psi')
The following example shall return the converted Pressure for Pa from 28 Psi.

11. from magiccal import GST
- GST Calculator calculates the GST value of the given price amount :
Syntax  : GST(<price>,<gst percent>)
Example : GST(12000,18)
The following example shall return the GST value for 12000 price along with 18% of GST on it.