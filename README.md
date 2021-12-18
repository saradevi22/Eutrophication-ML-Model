# Correlating Predicted Waterbody Nitrate Levels to Macrophyte Controls.


48% of lakes in North America are affected by eutrophication, a prevalent environmental issue in which the increased availability of nutrients leads to excessive growth of plants and algae. Eutrophication threatens aquatic ecosystems by lowering the pH of water bodies; this results in the creation of hypoxic waters which do not contain enough oxygen to support most aquatic organisms. We identified the need for a solution that addresses the overabundance of nitrogen and phosphorus in water bodies by naturally reducing their concentrations, effectively controlling the growth of existing algal blooms and preventing that of future ones. Our machine learning based project centers around predicting water nitrate levels (a strong indicator of eutrophication which is resource-intensive to measure) and then mapping that data along with user input to suggest macrophyte controls.

Macrophytes refer to aquatic plants that are visible to the human eye. They act as natural filtration systems in and around water bodies, uptaking nitrogen and phosphorus – among other nutrients –  present in agricultural run-off before or after it enters aquatic ecosystems in order to prevent algal blooms. Most macrophytes can survive in a wide range of temperatures and many thrive in conditions consistent with water bodies prone to eutrophication: slow-moving, nutrient-rich fresh, or brackish waters. Although they can survive in many parts of the world, most macrophytes flourish in a specific pH range. Due to their ability in keeping nutrient levels within appropriate ranges while maintaining a safe environment for native organisms, macrophytes could be used as biological controls to prevent and reduce algal blooms. 

The outputted nitrate level and the inputted pH value were associated with macrophyte biological controls. To construct this machine learning model, we uused SciKit Learn's Random Forest Regressor. All code was written in Jupyter Notebook using Python, which can be downloaded frorm this repository. The user interface, which was coded in Anvil and Python, can be reached through the Jupyter Notebook (however, because the web app requires a constantly running server, it may not be accessible). 

# Download Instructions 

The Jupyter Notebbook can be downloaded from this respository. For it to run, the necessary dataset and libraries should be installed. 

Note: This project was created through the Junior Academy, a program at the New York Academy of Sciences.
