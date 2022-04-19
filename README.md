# augur_view

HTML frontend for Chaoss/Augur, written with Bootstrap and served by Flask

To run as a local instance:

1. setup a virtual environment
    - `python3 -m venv env`
    - `source env/bin/activate`
2. Make sure you have the requirements installed
    - `pip3 install python3-venv flask pyyaml urllib3`
3. Run the app
    - `./run.sh`

Once the server is running, you can change the default `serving` url in `config.yml` and either restart the app or navigate to `[approot]/settings/reload` in the browser to connect to the desired augur instance.

For installation instructions on a server, see [installing](installing.md).

## Contributing

To get started with developing for augur_view, see [modules](modules.md).

Copyright 2021 University of Missouri, and University of Nebraska-Omaha

!-----------------------------------------------------------------------------!

## Sprint 3 

Where we left off -

We currently have two graphs displaying default data. The first graph displays the star count over time for the default project 'lodash' and the second graph displays forks over time for the default project. 

Progress - 

Day 1 Tuesday April 19th:

    Created drop down selectors for the desired data to be displayed and two repository selections. Allocated them dynamically based on api. Also reformatted the graphs for data display.


Goals - 


