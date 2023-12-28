# students-to-course-assigner
Script to assign students to courses using the CP-SAT solver of OR-Tools. Each student specifies which courses she/he desires (with priority). Each course has a min and max number of students. 

## installation
- create a virtual Python environment with at least Python 3.8: ```"path\to\python.exe" -m venv env_students-to-course-assigner```
- activate virtual environment: ```Scripts\activate```
- navigate to the ```dev```-folder
- clone the repository: ```git clone https://github.com/jlieberherr/students-to-course-assigner.git```
- ```cd students-to-course-assigner```
- install the necessary modules: ```pip install -r requirements.txt```
- run Jupyter lab: ```jupyter lab```
- execute the assigner in ```assigner.ipynb```