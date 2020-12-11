# m2aic2019
Material for the M2 AIC class

Clone this repo and make changes as desired. Keep the structure of the starting kit. The directory FILES contains additional useful files that will be needed when uploading the challenge to Chalab or Codalab.

Nov 19, 2019 release notes:
--------------------------
- changed iris.jpg to logo.jpg to make this generic.
- added a directory html_pages/
- added in starting_ kit a directory "utilities" containing a makefile to create a uploadable competition bundle.
The zip file created can be uploaded to https://codalab.lri.fr/competitions/ 
My Competitions > Competitions I'm running > Create competition

Usage:

	`cd starting_kit/utilities`
	
	`python make_bundle.py`

There are 2 ways of running the script: 
+ with sample data found in the starting kit or 
+ with the real "big" dataset. In this case run:

	`python make_bundle.py starting_kit_dir big_data_dir`# m1ai2021
