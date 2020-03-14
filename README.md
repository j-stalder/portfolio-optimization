# portfolio-optimization
This project represents an ESG-score optimized portfolio using a MiniMax model approach that has been implemented in a Jupyter Notebook. The project can be found in the same named folder.
The problem setting that is faced in this project can be described as followed:
As a Business-idea firm xy plans to launch a new app, in which clients are able to invest in a socially responsible manner. The app has to be able to compute for every portfolio an Environmental, Social and Governance (ESG) score between 0 and 100, where a higher score indicates a more responsible investment. Using an optimization process for each client a customized portfolio that takes into account the provided target values should be derived. Since firm xy is based in Switzerland, the initial investments universe comprises the stocks listed on SMI. The files prices1617.csv, prices18.csv and scores.csv contain the weekly closing prices of the SMI and its constituents for the years 2016-2017 and 2018 as well as the latest ESG scores for all SMI constituents, respectively.
For further guidance have a look at the Notebook and the comments that have been attached.  
In the folder "Basics of gurobi optimization" some simple optimization problems can be studied in order to get used to the mechanics of the Gurobi Solver. Covering a simple linear optimization problem, a convex optimization problem and a convex optimization problem.

## Getting started and prerequisites
The examples given in this course are made with the Jupyter-Notebook of the Anaconda Distribution using Python 3.x.x. In order to solve the mathematical problems this course uses the Gurobi solver for its conventional approach and intuitive utilisation.

### Installation of Gurobi
 As a student you can request a free academic license on their website: https://www.gurobi.com/. Once you filled out the registration you can download and install the latest version of the Gurobi sovler. After a restart of your computer log in with the account you created before and request a licence. Copy your licence-key and paste it into your command/terminal prompt.

### Installation of Anaconda
 Once your done with installing the Gurobi solver visit  https://www.anaconda.com/distribution/ and download the Anaconda distribution for your system (this course is based on Python 3.7). After the installation process open up the Anaconda prompt and type: conda install -c gurobi gurobi.    

## References
This course is inspired by the ideas and concepts of a same named course at the University of Bern.

## Author
* j-stalder(https://github.com/j-stalder)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
