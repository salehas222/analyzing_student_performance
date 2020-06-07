# analyzing_student_performance

The objective is to create a model which can predict the student score for maths, writing and reading using gender,the race/etricity of the student, the level of parents education etc.

### Understanding of Dataset

There are 8 attributes.<br/>
__Independent variable:__ gender, race/ethnicity, parental level of education,	lunch,	test preparation course	<br/>
__Dependentvariable:__ math score,	reading score,	writing score.</br></br>
*All the independent variables are __categorial variable__*</br>
__categories present in gender:__</br>
['female' 'male']</br></br>
__categories present in race/ethnicity:__</br>
['group B' 'group C' 'group A' 'group D' 'group E']</br></br>
__categories present in parental level of education:__</br>
["bachelor's degree" 'some college' "master's degree" "associate's degree"
 'high school' 'some high school']</br></br>
__categories present in lunch:__</br>
['standard' 'free/reduced']</br></br>
__categories present in test preparation course:__</br>
['none' 'completed']</br>

### Creating model
According to the goal, 3 dependent variable need to be predicted. I used multioutput regression. 
