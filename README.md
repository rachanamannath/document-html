# Document-HTML

Hey there folks,
I have created this document with HTML tags and structure. This document was part of the test that I had given during my interview process. Below is the product brief, style-guidelines and comments of the developer related to the product for documentation creation. I couldn’t include screenshots as this was a test and I didn’t receive any screenshots along with it. There were follow-up questions for the document I have added them in the main branch of repository.

**Breif:**
Chip Creator tool exceeds the performance of the previous generation of floor planning tools and we recommend using the newest version. It is relevant for using by Integrated Circuit designers. The tool does not loose performance when running on large designs, its performance is linear with the # of cells in the design. The tool support multiple CPU instances and no extra licenses are required; since 1 license has unlimited CPUs to use. The intelligent graphical user interface and batch tool is easy to use. You’re in complete control of the behaviour given the many options available. Preferences are shared between multiple users if desired using network files to make teamwork better. Chip Creator reads library information and the design information (such as schematic and clock speed) and then places and connects all of the design components on the chip using wires. Wires are metal but also sometimes polysilicon. When the run is complete you have an image of a chip that can be sent to factories for manufacturing in integrated circuit package. The chip then became part of phones or computer. At end of the run, there is always a log file and report that can be viewed in text reading/viewing software like notepad. It is recommended that you using third-party tool to verify the design to ensure that Chip Creator did everything correct. If there’s a problem, you can fix the issue found in Chip Creator and rerun the tool until the design is clean.

**Style-Guide:**
The following list is a basic set of rules to consider when developing the topic.
-	Use active voice and present tense.
-	Do not use “we” or “us” to refer to a corporate point-of-view.
-	Use the pronouns “you” and “your” when needed, but avoid overuse.
-	Avoid the word “user.”
-	Italicize all filenames and pathnames, including the file extension.
-	Be consistent with word use and style.
-	Use bold-faced fonts for menu options and buttons (for example, File &gt; Save and click the Close button).

**Engineer Comments:**
-	Start it from the command line. User must have valid license for starting Chip Creator GUI tool. Our GUI lets you fastly create many large designs with previews capability in realtime.
-	File menu has open design menu for importing library and design. Note, Tech lef must be read first. Tool also supports loading old project file instead of reading same input files everytime. Instead of menu, can enter read_file command in GUI prompt.
-	Use check &gt; inputs menu item to make sure all reading is ok and tool are ready for moving to the next steps. Incedentally, if INFO messages, usually this just tell the files that were read in before step.
-	Tool can create automatic chip outline (Run &gt; Create auto outline), or draw outline manually (Edit &gt; Draw outjline), or enter create outline command with value accordingly. Outline give desired chips size for CPU for example. Note, distance Units always microns.
-	Place all cells in chip border with Run&gt;place all cells or can use place_cells command with –all option Tool uses internal trade secret place-first algorithm that is better than the competitor by 5x performance.
-	Connect all wires with Run&gt;connect wires or connect command Wires are using different layers available from tech.lef file. You can custom the layers used if desired using set_layers command If wires can’t be connect, consider doing the place again. Place cells has random algorithm that can cause bad wire connecting sometime.
-	Chip is all done now! All cell placed correct according to rules and all wires connect all cells to eachother! User can run verify design if they want to make sure all was done accordingly. This is Verify &gt; All Design menu choice.



[HTML Document](https://rachanamannath.github.io/document-html/guide.html) for your reference. This is how it appears.
