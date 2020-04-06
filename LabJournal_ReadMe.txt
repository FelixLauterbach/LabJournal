HOW TO USE "LabJournal" BY FELIX LAUTERBACH:

Different Worksheets:

	"Chemicals":
	
		In here you find all the chemicals you may need for your reactions. Feel free to add any new substance to the respective table,
		e.g. add a new RAFT agent in the table "CTA" or a new monomer in the table "Monomers". Please do not change the order of the tables
		or conduct other foolish changes. The macros will appreciate that.

	Any other new sheet:

		Whatever reaction you are going to make (initiated by "Strg + n"), the respective macro will name the sheet according to your name, i.e. "FL" + increasing number in my case.
		There you will find all the data that you need for your reactions. The tables also evaluate most experimental results and give yo ua short summary.
		One worksheet is meant for one reaction. If you only make minor changes on this reaction you can simply copy + paste the table a few rows below the 
		old one and change the reaction name in the top left corner of the table. However, if you plan major change like exchange of reactants, please use
		a new reaction on another worksheet for it.
		There is also a header on each worksheet that summarizes the results of each reaction on the worksheet. This can be helpful if you make a lot minor
		changes and use a lot of different reactions on one worksheet. The header can be updated by pressing "Strg + h".


Visual Basic Editor:

	By pressing "Alt + F11" you enter the VBA for Excel. There you see a lot of modules and GUIs that all serve a different purpose. If you are new to this LabJournal
	you need to make a few minor changes to ensure that the worksheets are named with you initials and not mine. Therefore you have to go to the modules "modNewReaction"
	and "modRAFT" and search for "FL" and replace all of them with your initials (should be 3 per module). The same procedure needs to be done in GUI "UFRAFTOverview".
	To enter the code of the userform, press "F7", then search and replace.


Working with the LabJournal:

	When you want to make a new reaction, press "Strg + n". Then you can choose between any new reaction and other reactions that are implemented, e.g. RAFT.
	Just type whatever you want to conduct and another window pops up. Most of the GUIs are self-explanatory.
	After you finished entering all of your desired reactants and parameters, the respective worksheet you are in is filled with a table that now shows everything that you need.
	All cells with light borders in columns that have an additional "(TO BE)" should be filled for an appropriate calculation of your reaction. Additionally, the temperature, the
	number of samples, and reaction times can be filled in besides some other important parameters.
	
	If you now want to update the experimental results into the header on top of the worksheet, press "Strg + h" and the header should be filled.

	If you conducted a RAFT reaction and gathered all results, you can simply press "Strg + o" to get an overview of your reaction. Simply choose your monomer(s) and CTA from the
	comboboxes for one or two reactions and press the "Compare" button to show plots of the experimental results. If you already made GPC from your samples, insert a bitmap or any other
	graphic format into your worksheet, name it with "ReactionName_GPC" and it will be displayed as well.


Important shortcuts:

	"Strg + n": Opens a GUI to make a new reaction

	"Strg + h": Updates the header on the worksheet you are in
	
	"Strg + o": Opens a GUI to give you an overview of one or two RAFT polymerizations you choose.