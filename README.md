# resolution-setup
test  

nv modes: {*}1920x1080x32=1000; (with newline at end)  

delete configuration and connectivity  
reset64.exe  

add 1600x900 239.000hz in extension, 1920x1080 240 in detailed resolution  

delete configuration and connectivity again  
reset64.exe   

delete configuration and connectivity again  
change resolution to 1600x900 239hz in windows display adapter details  

delete 1600x900 239.000hz in CRU extension block  

reset64.exe one last time (this time without deleting configuration and connectivity folders)   

result:  
scaling=4  
