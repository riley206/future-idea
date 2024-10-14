**Play1** 

Otto Mattick manages a large warehouse-type space within a controlled environment, his staff historically spends a significant n inordinate amount of time on inventory and asset management.  He is required to keep strict inventory and asset controls that has necessitated verifying the exact location of numerous items several times a day.  When an item cannot be located on one of the mandated periodic checks the ensuing search to locate and document the situation becomes a high priority activity that has the potential of stopping all other ongoing efforts and impacting mission activities and schedule.  At the very least, both the periodic inventories and the resulting searches/responses are a drain on labor hours, distract from mission tasks, and impose a non-mission cost to operations.  Recently, Kamir Qwiq, head of IT wireless communications has implemented a wireless solution that allows Otto to use a mobile tablet to track the accountable items in real time, maintaining inventory throughout the space.  He has tagged the tracked items with an RFID label, and installed RFID readers strategically throughout the space.  In particular, there are RFID readers positioned at the entrance/exit to every room within the space so that every time a tracked items enters or leaves the room its movement generates a record of that change of location.  Further, he also has RFID readers at all the access points to the facility so that they can alert and alarm if a tracked item is inadvertently (or intentionally) removed from the approved area.  Finally, there are specific RFID readers located where the items are stored when not deployed throughout the facility, that serve as the automated, electronic “backup” to manual the check-in/check-out procedures.  Each time an item passes a reader a record of that occurrence is generated and forwarded to the RFID inventory management system where the tracking and inventory software maintains both the current location and the movement records of each item.  Further, the system automatically pulls the locations and inventory for the mandatory periodic reports, sets off an alarm and provides an alert when an item is moved out of its approved area, and records the time each item was checked out or returned to its storage location.

5.1.1	Technical Implementation 
The “Taking Inventory” play uses RFID technology for inventory management. In this section, we will be describing testing methods to assess recommended mitigations for the play. Tests may be technical, policy, or standard based as presented in Section 6.
Test 1: Test 1: Frequency Interference or Jamming of UHF RFID
Frequency interference and jamming may occur under intentional or unintentional circumstances, which are presented under this test. Potential mitigations for the play include:
•	Careful frequency planning and coordination: choose appropriate frequencies, use different  channels or frequency hopping, and coordinate with nearby wireless systems.
Improper planning and coordination may result in frequency interference and jamming that could limit inventory capabilities of deployed RFID labels and readers.
•	Shielding and Isolation: Strategically place readers and antennas, use shielded enclosures or RF-absorbing materials to minimize interference coupling.
Improper shielding and isolation of RFID readers and tags may also result in frequency interference and jamming.
•	Environmental Considerations: Be mindful of metal/liquid interference and identify/address external interference sources.

Metal and liquids near RFID technologies may result in frequency interference and jamming.
Test 2: To be developed
Brief description of test
•	Optimized Tag and Reader Design: Choose tags with anti-collision features, adjust 
reader sensitivity, and optimize antenna design/placement.
Test 3: Policy Review
Brief description of test
•	Prohibit certain items from being brought into the facility: it is important to consider what kind of items are accessible in the facility and how they may be used to inhibit the RFID tracking system. 

Test 4: Standard Verification

•	Does the deployed equipment meet ISO/IEC 23200-1 standards? 
