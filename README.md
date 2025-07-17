# AnyLogic-ALRcallerX
A library for running R code in AnyLogic software to deploy Machine Learning and Deep Reinforcement Learning in simulation experiments.
# Step to setup
**Step1:** Specify the R executable file location in the ALRcallerX library and configure the R interpreter path, <br>
-e.g: public static String RScript_Windows = "*C:\\Program Files\\R\\R-4.4.3\\bin\\x64\\Rscript.exe*"<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;public static String R_Windows = "*C:\\Program Files\\R\\R-4.4.3\\bin\\x64\\R.exe*"<br>
**Step2:** In AnyLogic, compile ALRcallerX library into portable format and export library file.<br>
**Step3:** Import the ALRcallerX library into the AnyLogic project and add it as a dependency.<br>
**Step4:** Install the *Rununiversal* communication package necessary for bidirectional data interaction in the R environment.<br>
**Step5:** Set up the machine learning function interface in the AnyLogic graphics panel and initialize the interactive interface.<br>
