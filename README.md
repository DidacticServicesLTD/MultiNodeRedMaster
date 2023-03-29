# Multi Node-RED Master

This project contains a scaffold for running 10x instances of node red.

It could be more optimal, but is designed to serve a specific purpose of group excercises run by Didactic Services Ltd


---

## Requirements
Node/npm must be globally installed -> https://nodejs.org/en/download

--

## To use

1. Clone the Repo


2. Run the install script (ONCE!)

This will install node-red into the root folder of the directory, and also provision and install the pallets for each sub-directory. Internet access must be avaliable for this installation step

```MAC_RUN_ME_TO_INSTALL_EVERYTHING.sh``` or ``` WINDOWS_RUN_ME_TO_INSTALL_EVERYTHING.bat```


3. Run the Launch file

This will launch all 10 instances of node red, on ports 1990 -> 1999

```MAC_RUN_ME_TO_LAUNCH_EVERYTHING.sh``` or ``` WINDOWS_RUN_ME_TO_LAUNCH_EVERYTHING.bat```

4. Tidy Up (Optional)

This will remove the node_modules folder, to make the directory lighter, but does not destroy the flows

```MAC_RUN_ME_TO_UNINSTALL_EVERYTHING.sh``` or ``` WINDOWS_RUN_ME_TO_UNINSTALL_EVERYTHING.bat```


---

## Info
the data_x folders contain a package.json file that lists which pallets should be installed, in each instance of node-red 