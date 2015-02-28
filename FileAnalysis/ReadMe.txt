Purpose:

This application analyzes the folder structre of the given path and generates a report of the all the files or directories that are duplicate.

Editing:

Copy the file into working folder and change the package name. Now you are good to go.

Use:

Create an object of the FileAnalysis.class and pass the path as an argument. Use startProcess() method to start the process. Use generateReport() method to generate report.

ex: FileAnalysis fa = new FileAnalysis("/home/DummyPath"); 
	fa.startProcess();
	fa.generateReport();
