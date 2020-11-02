# TEST:

python udemy-dl.py -q 720 -o "E:\Udemy" --sub-only -k cookies.txt https://www.udemy.com/course/ros-essentials/ --keep-vtt -s en

python udemy-dl.py -q 720 -o "E:\Udemy" --sub-only -k cookies.txt https://www.udemy.com/course/ros-essentials/ -c 1

python udemy-dl.py -q 720 -o "E:\Udemy" --sub-only -k cookies.txt https://www.udemy.com/course/ros-essentials/ -c 1 --keep-vtt


python udemy-dl.py -q 720 -o "E:\Udemy" --sub-only -k cookies.txt https://www.udemy.com/course/ros-essentials/ -c 1 --keep-vtt -s en

# All
python udemy-dl.py -q 720 -o "E:\Udemy" -k cookies.txt --keep-vtt -s en https://www.udemy.com/course/ros-essentials/

python udemy-dl.py -q 720 -o "E:\Udemy" -k cookies.txt --keep-vtt -s en https://www.udemy.com/course/ros-navigation/ 

python udemy-dl.py -q 720 -o "E:\Udemy" -k cookies.txt --keep-vtt -s en https://www.udemy.com/course/ros-actions/

# SUBTITLE 
python udemy-dl.py -q 720 -o "E:\Udemy" --sub-only -k cookies.txt --keep-vtt -s en https://www.udemy.com/course/ros-navigation/ 
['-o' ,'"E:\Udemy"' ,'--sub-only' ,'-k' ,'cookies.txt' ,'--keep-vtt' ,'-s' ,'en' ,'https://www.udemy.com/course/ros-essentials/']
# INFO:
python udemy-dl.py --info -k cookies.txt https://www.udemy.com/course/ros-essentials/
python udemy-dl.py --info -k cookies.txt https://www.udemy.com/course/ros-essentials/



