Download Link: https://assignmentchef.com/product/solved-ece-4250-7250-lab1-design-simulation-using-modelism-i
<br>
ECE 4250/7250VHDL AND PROGRAMMABLE LOGIC DEVICESLAB#1DESIGN SIMULATION USING MODELSIM II. ObjectiveThis objective of this lab is to make students familiar with the process of simulation andsimulation and verify the functionality of VHDL code by using ModelSim.II. Problems1. Creating a project in ModelSim and VHDL coding2. Compiling and debugging project files3. Simulating the designIII. Instructions1. Creating a projectOpen the program by clicking “Start” ! “All program” ! “Electrical Enge Software” !“Modelsim SE” ! “Modelsim”Next “File” ! “New” ! “Project”, then the following “Create Project” window (Fig.1) will appear.You need to enter a project name, a project location, and leave the “Default Library Name” to work.Click “OK” when finished.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/855.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/855.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.1 : Create New Project WindowA new window (Fig.2) will appear. You now have three options to add files to the project:• You can create new VHDL files (from scratch) and then add them to the project, or• You can add already existing files to the project, or• You can do a combination of the two operations by combining the two above operations.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/876.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/876.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.2 : New Project Window1.1 Creating a new VHDL file from ScratchClick on “Create New File” to create a new blank file. If you have closed the “Add items to theProject” window, then select “Project” ! “Add to Project” ! “New file”Then the “Create Project File” window will appear (Fig.3). Select an appropriate file name (we useAdder4 in this lab) for the file you want to add; choose VHDL as the “Add file as type” option and Toplevel as the “Folder” option. Click “OK” when finished.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/198.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/198.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.3: “Create Project File” dialog windowOn the “Workspace” section of the Main Window (Fig.4), double-click on the file you have just created(Adder4.vhd in this lab).

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/237.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/237.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.4: “ModelSim’s Main Window”Type in your code in the new window. For this tutorial, you will use below code.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/858.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/858.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.5: Code for Adder4.vhdSave your code “File” ! “Save”1.2 Creating your own FullAdder.vhdRefer to step 1.1 to open a new blank file (FullAdder.vhd), then make your own a full adder to use asthe component in Adder4.vhd.2. Compiling and debugging project filesSelect “Compile” ! “Compile All” to compile the projectThe compilation result is shown on the main window (Fig.6). A red message indicates that there is anerror in the code.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/965.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/965.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.6: Compilation error in the transcript windowDouble-click on the error (shown in red) in the main window. This will open a new window thatdescribes the nature of the error. In this case the error message is as follows (Fig.7),

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/839.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/839.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.7: Error messageDouble-click on the Error message. The error is highlighted in the source window (Fig.8)Fig.8: The error line is highlighted




<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/344.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/344.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>3. Simulating the design.Click on the “Library” tab of Workspace section in the main window and then click on the plus signnext to the work library. You should see the entity names of the codes that you have just compiled i.e.,“adder4” and “fulladder”. (Fig.9)

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/820.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/820.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.9: Library windowDouble-click on the top level entity to load the design (In this lab, adder4 is the top level entity). Thiswill open a third tab “sim” in the main window.Now select “View” → “Objects” from the main window to open the Objects window if it does notappear (Fig.10).

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/738.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/738.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.10: sim window and Objects windowThen, select “Add” → “To Wave” → “All items in region” to open wave window (Fig.11).

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/650.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/650.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.11: Wave windowNow you are ready to simulate this design. Before you do this, you need to set the input signal value. Inthe wave window, right-click on the signal that you want to set the value, and select “Force” (Fig.12),then it will appear a new window (Fig.13). Enter the value in the new window, then click OK to finish.Repeat this to set every signal that you want to set the input value. (In this lab, you need to set signal a,signal b, and signal ci. For example, Set a &lt;= 0101, b &lt;= 0111, ci &lt;= 0.)

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/583.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/583.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.12: Click Force to assign the value

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/375.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/375.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.13: Force signal windowNow set the simulation period and click the run button next to it (Fig.14).

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/793.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/793.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

Fig.14: Run the simulation<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/416.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/416.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Fig.15: Simulation resultIV. Lab Requirements:Complete the above lab procedure and print the final results. Simulate at least 3 additions showingthat your design can work successfully. Then, briefly describe about the function and the syntax ofport-map statements? For example, in our Adder4.vhd, why does the order have to be port map(A(0),B(0),Ci,C(1),S(0))?