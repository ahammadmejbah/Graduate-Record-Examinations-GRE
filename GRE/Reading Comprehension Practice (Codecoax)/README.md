RC_Practice_Utility
===================

Run the file RC.html to start using the utiliy.<br><br>
The utility takes an indexed array with the reading comprehensions and the respective questions and answers. The following is the format of the array.

data[passage_index][0]=passage data <br>
data[passage_index][1]=Questions (Array) <br>
data[passage_index][1][Question_index][0]=Question <br>
data[passage_index][1][Question_index][1]=Answer <br>
data[passage_index][1][Question_index][2]=Option1 <br>
data[passage_index][1][Question_index][3]=Option2 <br>
data[passage_index][1][Question_index][..]=Option.. <br>
data[passage_index][1][Question_index][..]=Option.. <br>
data[passage_index][1][Question_index][N]=OptionN<br>

See the data.js file for example data format. Make sure to replace the data.js file with your data file (or edit RC.html to point to your data file)
<br>
<script src="data.js" type="text/javascript" charset="utf-8"></script>
