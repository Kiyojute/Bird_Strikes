 ## Project Objective <br />
 Analyze data from the FAA (Federal Aviation Administration) for the years of 2019 to 2024 involving various bird strikes on airplanes. After analyzing the data I hope to provide insight into the conditions these strikes most likely occur, conditions as in airlines involved, phase of flight, altitude strike occurred at, etc.. Theoretically these results could be use to identify problem areas that need to be addressed and/or mitigated. Bird strikes cost airlines, airline customers and private individuals countless dollars in damages and lost time yearly not to mention wildlife that are struck and killed.    


 ## Set Up ##
  Download and install VScode: https://code.visualstudio.com/download  
  Install Jupyter Notebook: You can browse and install extensions such as Jupyter Notebook from within VS Code. Bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X). Search for Jupyter Notebook then select the Install button. <br />

  Once you're in Jupyter Notebook in VS Code you'll need download and load the following github repo: https://github.com/Kiyojute/Bird_Strikes and set up and run a virtual environment. <br />
  Setting up and running a virtual environment:  
  First open up a Bash terminal by Ctrl + `` (backtick) on Windows and Linux, or Cmd + `` on macOS. This will open the integrated terminal where you can run Bash commands if Bash is set as your default shell.  
  Activate the virtual environment by typing in the following:  
  *on Windows*  
  virte/Scripts/activate  
  *on macOS and Linux*  
  source virte/bin/activate <br />
  When setting up the project on a new system, install all dependencies using: <br />
  pip install -r requirements.txt  



  ## Overview ##  
  What you should expect from this project once it's running is for it to run flawlessly with no hiccups, catastrophic crashes or dumpster fire shutdowns. Translation: 60% of the time, it works every time.


  **Data Summary/Sources** - The folowing datasets for this project were downloaded from Kaggle:  
  
  'bird_strikes.csv'  - 26 columns 25429 rows <br /> 
  https://www.kaggle.com/datasets/ourwit/bird-strikes-in-aviation-aircraft-collisions  
  
  'airport.csv'  - 14 columns 7698 rows <br /> 
  https://www.kaggle.com/datasets/maroofabdullah/airports-csv  
  
  *See licenses below*  


  **Technologies Used** <br />
  *Jupyter Notebooks* - was utilized for it's ease of collaboration, real time code execution, data manipulation and clear visualizations.  
  *Pandas* - was used for it's efficiency of data manipulation and analysis of bird strike and airport csv files.  
  *matplotlib* - provided great customizable visualizations on the data.  
  *seaborn* - another great package to provide easy to use visualizations in displaying the data.  
  *SQLite* - was utilized for this project as a requirment and for it's simplicity and easy to understand straitforward application.  
  *Various AI Tools* - Various AI tools such as Microsoft Copilot and Duck.ai for quick reference to commands needed and debugging of errors recieved when running code. <br />

  ## Data Dictionary <br />
  *'bird_strikes.csv':* <br />
  RecordID - ID assigned by FAA <br />
  Airport - Name of airport <br />
  MakeModel - What people were flying in <br />
  Effect - Outcome of bird strike <br />
  FlightDate - Date of Flight/Calamity <br />
  Damage - If things got broken <br />
  Airline - Operator of aircraft <br />
  State - Location of airport <br />
  FlightPhase - Phase of flight strike occured <br />
  Precipitation - To rain or not to rain that is the question <br />
  Remarks - A human commenting about the bird strike <br />
  Clouds - Clouds or not <br />
  BirdSpecies - The offending birds or other wildlife who must not be named <br />
  Cost - The benjamins it takes to fix the damage <br />
  Altitude - Height in sky the strike occured <br />
  PeopleInjured - Number of people going to lawyer up and sue <br />
  *'airport.csv':* <br />
  airport - Name of airport <br />
  city - City airport located in <br />
  country - Country airport located in <br />
  iata - Three letter code for airport <br />
  latitude - East-west lines on globe <br />
  longitude - North-south lines on globe <br />
    

  **Licenses** <br />
  'bird_strikes.csv': MIT - https://www.mit.edu/~amini/LICENSE.md <br />
  'airport.csv': CC0: Public Domain - https://creativecommons.org/publicdomain/zero/1.0/

