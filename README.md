# CoPAS
Community Packages for Airborne Science (CoPAS) is a Github project designed to
facilitate the installation, setup, and integration of open source software and
packages related to cloud physics, in-situ airborne data.

Download/Clone CoPAS Distribution
---------------------------------
- mkdir ${HOME}/CoPAS
- cd ${HOME}/CoPAS
- git clone https://github.com/daviddelene/CoPAS.git

Download Packages:
------------------
- mkdir ${HOME}/CoPAS_Packages
- cd ${HOME}/CoPAS_Packages
- ${HOME}/CoPAS/CoPAS.py

Update Package:
---------------
- git commit file
- git push origin master

Projects Supported:
-------------------
- Airborne Data Processing and Analysis (ADPAA)
    https://sourceforge.net/projects/adpaa/
- Airborne Data Testing and Evaluation (ADTAE)
    https://sourceforge.net/projects/adtae/
- EUFAR General Airborne Data-processing Software (EGADS)
    https://github.com/eufarn7sp/egads-eufar
- System for OAP Data Analsis (SODA)
    https://github.com/abansemer/soda
- University of Illinois OAP Processing Software (UIOPS)
    https://github.com/joefinlon/UIOPS

Setup ADPAA via CoPAS:
----------------------
- Website to Download or Clone CoPAS:
https://github.com/daviddelene/CoPAS.git
- Clone Repository:
git clone
https://github.com/daviddelene/CoPAS.git
- Setup Aircraft Software:
mkdir ~/CoPAS_Packages
cd ~/CoPAS_Packages
~/CoPAS/CoPAS.py
- Setup ADPAA on Linux:
~/CoPAS_Packages/ADPAA/bin/adpaa setup
- Setup Data Set:
cp –r ~/CoPAS_Packages/ADTAE/TestData/FlightData/20150728_153107 ~/20150728_153107-SandBox

