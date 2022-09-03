# Climbing_Performance_Myth_Tester

Hello! This repository currently houses a single Excel file which will periodically be updated. The file includes information regarding rock climbers' bouldering performances at varying gyms and at differing times. 

DATA COLLECTION IS ONGOING! If you would like to contribute your own data (which would be very much appreciated) feel free to reach out (I am currently transitioning my means of data collection to make this easier for contributors)! If submitting data, please consult the Excel file included here to get an idea about the sorts of information I am interested in. Submissions formatted in way friendly to R, SQL, or Python (any standard delimiter is acceptable).

NOTE: If submitting data, please include the same column headers as those included in the Excel file. If they are different or absent, your data will still be used but it just makes it easier for me when I am compiling the data sources into a single file. The headers are as follows (in this order):

Date, Type_of_Climbing, Location, Grade, Attempts, Completed, Crux_Move_Type(s), and Repeat.

Date refers to the date either when the climb was first completed or when the latest attempt was made. Type_of_Climbing is "bouldering", "lead", "top rope", or "free solo". Location is either the name of the climbing wall/gym where the climb is located or if climbing outdoors, simply "outdoors" [If you wish to specify an outdoors location further, that is okay but please include the word "outdoors", e.g. "Colorado outdoors"]. Grade is the difficulty of the route/boulder [Any of the following scales are acceptable: French (e.g., 7C, V-System (e.g., V9), 5 point system (e.g., 5.12c)]. Attempts is the number of attempts made up to and including completing the climb. Completed is either "yes" or "no". Crux_Move_Type(s) is the type of holds/moves that are the hardest parts of a climb (all sorts of descriptors are acceptable here so long as they are in English. For example, "crimps", "sloper", "dyno", and combinations such as "pinches/crimps" are all acceptable). Finally, Repeat is either "yes" or "no" [yes means that the climb has been done before by you and you are repeating the route/boulder]. 

Once the data collection process has been completed, I will begin working on the following components:

1. Predictive algorithms for the efficiency (attempts to completions ratio) of a given climber.
2. An interactive dashboard that allows users to imput their own data (probably in the form of summary statistics) and have said dashboard return 
   information about how a user measures up to different climbers (e.g., comparisons to average, advanced, and [if possible] professional climbers).

These components will likely be modified as the project progresses and should not be taken as strict descriptions of the expected final product(s). 

Some Final Notes:

If you would like to be cited in the final project for providing data, please include your name, title (if applicable), and professional/academic association(s) (if applicable). If you do not explicitly mention this, I will, for the sake of the anonymity of other contributors, exclude any identifying information from any and all products resulting from this research. 

This project is being worked on by me alone and is not in any way associated with any particular institution. As such, I cannot offer any financial compensation for contributing to this research, be it offering data or suggestions with the code. 
