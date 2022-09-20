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
![a](https://raw.githubusercontent.com/sunurnuts/resolution-setup/main/temp2.png)  
![b](https://raw.githubusercontent.com/sunurnuts/resolution-setup/main/temp.png)  
![c](https://raw.githubusercontent.com/sunurnuts/resolution-setup/main/image.png)  

i assume you can do this reversed with 1920x1080 in the extension block and 1600x900 as native  
no need for reset-all  
scaling=4 somehow makes everything sharper  
i assume its cuz nvidia or windows is completely ignoring that folder, if u put scaling=1 i assume it stops ignoring the configuration folders   
i dont know whats going on  
