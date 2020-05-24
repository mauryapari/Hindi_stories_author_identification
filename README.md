# Hindi_stories_author_identification

## Pre-reqistis
- Windows OS specific:
  - [Git For Windows](https://gitforwindows.org)
- Microsoft Excel
- Text Editor(preferably Notepad)
- Python 3.0+
- Jupiter Notebook
- Weka Machine Learning Tool.

## Basic Setup
- Follow this [link](https://medium.com/@kswalawage/install-python-and-jupyter-notebook-to-windows-10-64-bit-66db782e1d02) to install Python along with Jupiter notebook in your system.
- Follow this [link](https://sourceforge.net/projects/weka/files/weka-3-8/3.8.4/weka-3-8-4-azul-zulu-windows.exe/download?use_mirror=nchc) to download Weka machine learning tool.For further assistence refer to this [video](https://www.youtube.com/watch?v=R90MCU9nqOM).

## Instructions
1. Clone the repo or download it in zip format.
2. If you followed the link to install Jupiter Notebook as mentioned above.Place the above code folder in opencv/scripts.
3. Else place the folder wherever your Jupiter notebook Files are being saved.
4. Change the directory to where your text is present and run the code.
5. Once fetures for the whole corpus of an author are extracted, import the txt files like conjuction.txt etc to excel files.
6. Refer to excel file above for viewing the name of features along with names of autor's stories.
7. Convert these excel files into csv files.
8. Convert thse files to arff format using this [link](https://www.youtube.com/watch?v=tS6qFxNDrMc) in weka.
9. once done load the arff files in explorer section and choose J48 in classifier section.
10. Go to Select attributes section and click on start.Form a new dataser using these attributes.
11. Run different algorithms on this dataset for determining the best algorithm.
