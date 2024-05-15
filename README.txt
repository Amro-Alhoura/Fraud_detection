Description:

The Data.xlsx file includes the following data:
device_id — device identifier*
identity — user identifier
bank — bank identifier
device_fingerprint — digital fingerprint of user’s device**
gpu_vendor — GPU manufacturer
screen — screen resolution
os — operating system
browser — browser
ips — IP addresses

The Data.xlsx file has data on devices and personal accounts of users, suspected to be involved in cross-bank fraud. 
Among them there are fraudulent (compromised) device 91b12379-8098-457f-a2ad-a94d767797c2 (Bank4) and user account 0007f265568f1abc1da791e852877df2047b3af9 (Bank8).

The Task:

01 Extract as much information as possible from the IP address (country, city, subnet, time zone) 
and User agent (OC + version, browser + version, mobile/not mobile device, etc.) and compile it in a separate *.csv file.

02 Find all user accounts associated with compromised accounts, demonstrate and explain these connections, including via device
parameters and/or location *** (provide arguments in the report).

03 Present the result visually (for example, in the form of a network and/or any other visual format for presenting data that you deem appropriate).


* One real device can have several identifiers (device identifier is a cookie file)

** Device fingerprint is a function of the device parameters, identical physical devices may have similar fingerprints,
(for example, when one device runs a newer version of software than the second device) 

*** IP address can be dynamic
