# Project Overview

The **Sales Report Generator Bot** is a UiPath automation designed to streamline the sales reporting workflow. Leveraging UiPath's robust capabilities, this automated process efficiently extracts raw data from a CSV file, creates a comprehensive sales report using an established Word template within a UiPath Flowchart, converts the generated report into a standardized PDF format through a Windows application, and systematically organizes and relocates the files to a designated folder.

![Sales Report Generation Process Flow](https://github.com/pooh2304/UiPath-Projects/assets/51374683/ce88b9b8-d619-41a1-9d80-91dca8efc1bf)


To retrieve all the files present in a directory: Directory.GetFiles("directoryName")  <br>
To get full path of the file: Path.GetFullPath(“fileName”)  <br>
To get full path of the directory: Environment.CurrentDirectory + "\directoryName"  <br>
To retrieve all the directories under a folder: Directory.GetDirectories("Our_Path")
