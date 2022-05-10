echo off

md Gomonok
cd Gomonok
md Marina
cd Marina
md Sergeevna
cd..
cd..

pause

cd Gomonok
echo > 18.12.2000.txt
cd Marina
cd Sergeevna
echo > 4.txt
cd..
cd..
cd..

pause

del Gomonok /S /Q /F

pause

cd Gomonok 
cd Marina
rd Sergeevna
cd..
rd Marina
cd..
rd Gomonok 

pause