# Energy Market and Battery Optimization External Project

Group Members:  
- Megan Soo
- Wai Lam Wong
- Laura Vander Slott
- Seth Ng Jun Jie
- Che Yao Bong

This university project aims to develop an algorithm to maximise the revenue of a grid connected battery for two different scenarios; with perfect future price visibility (mandatory task, only for VIC) and without (bonus task, across the four states provided). External datasets from an energy company were provided to us to optimise our algorithms. One of them includes the spot prices, amount of power used to charge or discharge from the battery, the market revenue, and the opening & closing capacities of the battery in period intervals of 30 mins from 1/1/2018 to 30/6/2021. Another dataset includes the demand and supply for energy consumption across Victoria, New South Wales, South Australia, and Tasmania for the past 3.5 years.

For more information about the project outline please take a look at 'Project Spec.pdf'.

To read about our methods, analyses, findings, and conclusion please take a look at our presentation here:
https://www.canva.com/design/DAErvNNmmvs/dPLR3pgYKCrdRK3e6jjcWA/view?utm_content=DAErvNNmmvs&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton#5

# Repository Overview
- `code`: Contains `analysis`, `modelling` and `deprecated` folders which contain the various notebooks for the project.
- `data`: Raw dataset that was provided.
- `instructions`: Instructions provided by client. Also includes a .txt file that eases understanding of formulas from the 2021_UMelbAppliedData_Worked_corrected Excel file.
- `meeting_minutes`: Documented minutes for any meetings conducted by the team.
- `plots`: Plots that were generated in any of the notebooks are stored here.
- `results`: Files that contain results generated from notebooks in `modelling`, as well as outputs from the checking scripts in `code` folder.
- `requirements.txt`: Python packages that are required to run all the notebooks in `code` folder.
