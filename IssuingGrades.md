# Grade Submission

All students who finished the class without withdrawing need to receive a final grade.  This includes students who you have elected to offer Incomplete grades to.  Check the [Incomplete Grades Guide](Incompletes.html) for more info on requirements and implementation of the Incomplete process.

## Pulling Data from Canvas

### Final Grade Data

The best place to start is by downloading the grades spreadsheet from Canvas Grade Center.

1. While in Grade Center, click the Settings Gear.
2. Ensure the box _"Treat Ungraded as 0"_ is checked.  
This will ensure students who did not submit assignments won't have those assignments removed from consideration in their final grade.
3. From the _Grade Center_, click **Export**.
4. Click **CSV File**.  
This will download the grades as a comma-separated file.
5. Open the downloaded spreadsheet in the editor of your choice. 
6. _(Optional)_ Delete unneeded columns
The only data columns required for grade submission are **SIS User ID** and **Unposted Final Grade**, though it is recommended to keep **Student** as well to simplify adding last-date-of-attendance for students with F-grades.

### Last Date of Participation (Students with F's and Incompletes)

For _ONLY_ students with F-grades or Incompletes, you'll need the _Final Date of Participation_ for financial aid purposes. First, in the downloaded grading spreadsheet, add a column for this data.  

_NOTE: Ensure this column is not auto-formatted (in Excel, select the column, right-click, **Format Cells**, and select **Text**). If this isn't done, the date-format will be overwritten when you save the file and will not be accepted by the system for upload._

#### For each student with an F grade...
1. From the Course **Navigation** sidebar, select **People**.
2. After the roster loads, search the student's name.
3. Pull the **Last Activity** date.
4. Enter the last date of activity for the student in the respective column in the format MM/DD/YYYY (e.g. 01/04/2019).  
   - NOTE:  The last date the system accepts is the last day of Dead Week (Friday before Finals week). This day can be found on the [Academic Calendar](https://registrar.oregonstate.edu/osu-academic-calendar). Enter this date for any students whose participation outlasted Dead Week.
   - NOTE:  This format is **required**. The upload will fail for students who have date entries which don't match this format.

Repeat this process for any students you'll be giving Incompletes to.

_NOTE: For these students, the final grade should I/X where X is the letter grade they'll receive if they never complete their course materials._

## Uploading Grades

1. Access the MyOSU Portal by opening [MyOSU](https://myosu.oregonstate.edu/). 
2. On the bottom right of this page is a **Banner Self-Service** link.  Click this to get a dropdown, then under the **Faculty & Advisors** select **Final Grades Menu** and finally **Final Grades - File Upload**.
3. Select the term you wish to enter grades for.  
_NOTE: From this point on, if you wish to change the Term or Course you may click **RETURN TO MENU**, then **Final Grades Menu** and finally **Term Selection** or **CRN Selection** links._
4. The page which opens is an archaic interface, but there are only a few fields which you need.
    - For **Path/Filename** select **Choose File** and select the .csv file you've been modifying.
    - You may use EITHER **Subject/Course** OR **CRN** to select the course whose grades you're uploading. If you select both, the upload will fail.
    - For **Data Item Name** and **Location** associate the columns in your .csv to the appropriate data field.  This is required only for **Student ID** (SIS User ID), **Grade** (Unposted Final Grade), and **Last Attend. Date** (For F-grade students and Incompletes).
5. Click **Process File**.

## Check for Missing Grades

It's always a good idea to check your work.  To verify there are no missing final grades...

1. **RETURN TO MENU**
2. **Final Grades Menu**
3. **View Missing Final Grades**
4. Select the Term and Submit.

## Modifying Posted Grades

Sometimes we have a reason to modify an existing grade.  There is a period of approximately one week after the grading window closes (5pm Monday after the term ends for Fall/Winter/Spring) where we cannot make changes, but outside that window we can change a final grade at any time. To do so...

1. Access the MyOSU Portal by opening [MyOSU](https://myosu.oregonstate.edu/).
2. On the bottom right of this page is a **Banner Self-Service** link.  Click this to get a dropdown, then under the **Faculty & Advisors** select **Final Grades Menu** and finally **Final Grades - Change Posted Grades**.

## Spring Term Preliminary Grades

The University must begin the process of issuing diplomas earlier in Spring Term than the final grade data is available.  To deal with this, we have a process wherein we will issue preliminary grades about halfway through Spring Term.  These are relevant only if the student is failing. Depending on your course, you may have only a few of these or your entire class might have applied for graduation.  For smaller student groups, you may use Keyed Entry, but for larger groups it is recommended to generate a file as follows.

1. While in Grade Center, click the Settings Gear.
2. Ensure the box _"Treat Ungraded as 0"_ is unchecked.  
This will ensure that only already-graded assignments will contribute to the generated grade. If the student has missed submission of already-due assignments, issuing a 0-grade at this time is appropriate.
3. From the _Grade Center_, click **Export**.
4. Click **CSV File**.  
This will download the grades as a comma-separated file.
5. Open the downloaded spreadsheet in the editor of your choice.
6. _(Optional)_ Delete unneeded columns
The only data columns required for grade submission are **SIS User ID** and **Unposted Current Grade**, though it is recommended to keep **Student** as well.

To access the entry portal...

1. Access the OSU Final Grades Portal by opening [MyOSU](https://myosu.oregonstate.edu/).
2. On the bottom right of this page is a **Banner Self-Service** link.  Click this to get a dropdown, then under the **Faculty & Advisors** select **Spring Term Preliminary Grades Menu** and finally **Preliminary Grades - File Upload** or **Preliminary Grades - Keyed Entry**.

After this point, upload is identical to Final Grades.
