# BMI:octocat:
Body Mass Index application written in java.

# Description
  BMI calculator is the exact desktop version for BMI Calculator android app by Splended Apps.
  It follows and verifies all the conditions provided in the android app.

# Analysis of BMI 
**Description:** BMI Calculator has three input fields age, height and weight. App takes input in different scale meters vary by selecting the one of the combo box list. According to these inputs there are three output fields BMI, IDEAL WEIGHT and FAT. Beside these outputs app also shows the BMI Classification that changes by changing the BMI.
## Input Validations: 
* **Age:** App takes minimum age 0 and maximum age 999.
* **Gender:** Male or Female gender can be selected only.
* **Height:** You can change height scale to cm or FT + IN form by selecting one of the combo box list. In feet + inch form app takes 0 to 999 feet and 0 to 9999 inch and in the form of cm it takes 0 to 99999 cm.
* **Weight:** You can change weight scale to ST + LB, LB or KG by selecting one of the combo box list. In KG form app takes 0 to 999 KG’s, app takes 0 to 99999 pounds and 0 to 999 stone and 0 to 99999 pound.
## Output Validations:
* **BMI:** BMI ranges in between 0 and 100.
* **IDEAL WEIGHT:**
	* App used the Dr. DR Miller formula to calculate the ideal weight of the body. The output of the ideal weight is from 0 to 440 pounds or from 0 to 220 kg.
	* App only shows the ideal weight if height is greater than 20 inch.
	* App only shows the ideal weight if height is greater than 51cm for men and greater than 53cm for women.
* ***Dr. DR Miller’s formula***
	* **Formula of Ideal Weight for Men**
		* IDEAL WEIGHT = 56.2kg + 1.41kg / inch over 5ft
	* **Formula of Ideal Weight for Women**
		* IDEAL WEIGHT = 53.1kg + 1.36kg / inch over 5ft
* **FAT:**
	* FAT ranges in between 0 and 100 percent.
	* App used BMI to calculate the FAT.
	* Following are the formula’s used by the app to calculate the FAT of a body.
	* **Formula of Fat for Men**
		* FAT = (1.20 * BMI) + (0.23 * AGE) – 10.8 – 5.4
	* **Formula of Fat for Women**
		* FAT = (1.20 * BMI) + (0.23 * AGE) – 5.4
