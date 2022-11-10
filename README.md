# fed-dashboard
A simple dashboard to view federal economic data.

This system uses the included CSV file of federal economic data to populate the dashboard.  

This system goes through a bit of data processing from various angles to construct the charts.

This is a python project using Dash and plotly to contextualize federal economic data retreived from the FRED system.

To use:

1. Download the files in the repository to a directory.
2. In the support_functions.py file, ensure your paths are correct.

**NOTE** - I developed this on a Mac and run it on a Linux machine.  Files are set to reside in a subdirectory "data" under the main folder.

3. Review the requirements.txt and make sure all libraries are installed.
4. Run the main.py file using 'python /path/to/directory/main.py'
5. Navigate your browser to the ip address of the machine (perhaps 127.0.0.1 or other if installed remotely) on port 8050.
6. Enjoy!


![](https://github.com/kushal-from-dolpo/Federal-Reserve-Economic-Data-Analysis/blob/main/github_image.gif)
