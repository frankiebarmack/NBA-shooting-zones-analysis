# NBA-shooting-zones-analysis
we scrape some shot distribution data from nba com stats, then visualize it, then create an algorithm to optimize shot distribution for playoff teams. 

# How to Run
To successfully run this project, you will need to specify the paths to two folders: yearly team midrange fga and yearly team ortg.

In the Python code, locate the with open statements in the section where team midrange FGA and offensive ratings are loaded. Replace the placeholders with the correct paths to your local folders where these files reside.

Here's a code snippet example:

##### Open team midrange FGA for all 8 years
for year in years:
    with open(f'{your_path_to_yearly_team_midrange_fga_folder}/{year}TeamMR.txt', 'r') as file:

##### Open team offensive rating in the playoffs for all 8 years
for year in years:
    with open(f'{your_path_to_yearly_team_ortg_folder}/{year}oRTG.txt', 'r') as file:
        

Replace your_path_to_yearly_team_midrange_fga_folder and your_path_to_yearly_team_ortg_folder with the complete paths to the respective folders on your machine. You can download them from the repository
