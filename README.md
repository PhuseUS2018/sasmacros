## use-R and SAS

SAS is an industry standard for statistical analysis enablingaudit trail, QC, storage of log files and powerful reporting capabilities.
R which is open source has wide user community and efficient customizable data visualization tools.As a result, tools to integrate R with SAS are becoming increasingly prominent.Though SAS cannot be accessed through R, SAS has a capability to run R through Proc IML and several other customizable macros, provided user has R installed on their desktop. R2SAS, R2SAS2PDF & SAS2SHINY are such macros integrating thecapabilities of SAS and R.

%R2SAS[1] allows SAS to run the Rscript through the command line from within SAS.                            %PDFplot1x1[2], %PDFplot2x1[3], %PDFplot2x2[4] can be used to create pdf’s of 1, 2 or 4 plots from R script.These pdf’s have customizable header and footer to include anlayses folder, username, pagination.%SAS2SHINY demonstrates output of shinyapp through shinypkv package[5].

### Prerequisites
Installation of both SAS and R on the user's system or server

The use of global variables can make for some very impressive coding shortcuts, but a simple example, namely setting the path for the reporting effort is used for this effort

/*************************************/
/*** Set path for reporting effort ***/
/*************************************/
%let path = C:\SAS4CPMS;

/*	Wherever the reporting effort is to be produced, this path is entered. NOTE that there are no quotes. The path variable &path is defined as the characters C:\SAS4CPMS, which means wherever we type &path, these characters will appear before SAS process the command.
A directory structure for reporting is standardized for all reporting efforts

![]({{site.baseurl}}/)![reporting structure]({{site.baseurl}}//reportin.png)
### Contacts
-Pragathi Kotha Venkata -GSK,US

### References: 
[1][ https://github.com/PhuseUS2018/sasmacros/blob/master/R2SAS ]( https://github.com/PhuseUS2018/sasmacros/blob/master/R2SAS )

[2] [https://github.com/PhuseUS2018/sasmacros/blob/master/PDFplot1x1 ](https://github.com/PhuseUS2018/sasmacros/blob/master/PDFplot1x1 )

[3][https://github.com/PhuseUS2018/sasmacros/blob/master/PDFplot2x1 ](https://github.com/PhuseUS2018/sasmacros/blob/master/PDFplot2x1 ) 

[4][https://github.com/PhuseUS2018/sasmacros/blob/master/PDFplot2x2 ](https://github.com/PhuseUS2018/sasmacros/blob/master/PDFplot2x2 ) 

[5] [https://pkvreddy.github.io/pkv/](https://pkvreddy.github.io/pkv/)

[6][https://github.com/PhuseUS2018/sasmacros/blob/master/PLOT2PDF-template](https://github.com/PhuseUS2018/sasmacros/blob/master/PLOT2PDF-template) 

[7][https://github.com/PhuseUS2018/sasmacros/blob/master/SAS2SHINY](https://github.com/PhuseUS2018/sasmacros/blob/master/SAS2SHINY)
