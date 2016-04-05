# Instructions for Creating a Clone of ISPD 2013 Contest Benchmark Set

##	Setting Up a Copy of the Set of ISPD 2013 Contest Benchmarks

### Commands for a UNIX-like Operating System 
- git clone git@github.com:eda-globetrotter/ispd2013contest-benchmarks.git
- git lfs track "*.tgz" "*.gz" "*.sdc" "*.spef" "*.v" "*.tar" "*.bz2"


### Command to Verify the Types of Files Tracked by Git Large File Storage (LFS)
- git lfs track





# Organization of the Repository
+ ispd2013
	- cordic benchmark
	- des benchmark
	- edit_dist benchmark
	- fft benchmark
	- lib
		* (Process) technology library, or the cell library (used
			during the technology mapping step of logic synthesis).
	- matrix_mult benchmark
+ netcard
	- .sdc file
	- .spef file
	- .v file
+ Final






















