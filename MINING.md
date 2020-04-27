## BITCOINHEALTH coin MINING

Early MINING can be performed on Windows and Linux computers with GPU's installed.

# Windows:

To Mine on Windows PC's with GPU:

1. Install the Windows Ubuntu plug in. Instructions here : https://docs.microsoft.com/en-us/windows/wsl/install-win10
2. Select: Ubuntu 16.04 LTS or Ubuntu 18.04 LTS
3. Follow the Unix-Build.md read me for install instructions. 
4. Go to Bitcoinhealth applicaton directory  > Bitcoinhealth/src
5. Type  > explorer.exe .   to launch Windows Explorer to view your Ubuntu Bitcoinhealth src directory.
6. Create the following file bithealthbatch.sh from Windows Explorer
7. Add the following :

While :
do
./bitcoinhealth-cli:
generate 1
done

8. Return to Ubuntu cli. Execute ./bithcoinhealthd  or src/qt ./bitcoinhealth-qt
9. Open second Ubuntu cli window.  Go to  > bitcoinhealth/src
10. Execute > ./bithealthbatch.sh
11. Minining begins.  Checking Mining status in QT Window. 
