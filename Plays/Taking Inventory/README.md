# Play 

Here is a play. Matt wants to use RFID to take inventory. (continued story)

# Technical Implementation 
The “Taking Inventory” play uses RFID technology for inventory management. In this section, we will be describing testing methods to assess recommended mitigations for the play. Tests may be technical, policy, or standard based as presented in Section 6.

 - Test 1: Frequency Interference or Jamming of HF RFID [Tests/RFID/HF/Frequency Interference And Jamming](../../Tests/RFID/HF/Frequency%20Interference%20And%20Jamming/)
   - Frequency interference and jamming may occur under intentional or unintentional circumstances, which are presented under this test. Potential mitigations for the play include:
 - Careful frequency planning and coordination:     
    - choose appropriate frequencies, use different  channels or frequency hopping, and coordinate with nearby wireless systems.
   - Improper planning and coordination may result in frequency interference and jamming that could limit inventory capabilities of deployed RFID labels and readers.
- Shielding and Isolation: 
  - Strategically place readers and antennas, use shielded enclosures or RF-absorbing materials to minimize interference coupling.
Improper shielding and isolation of RFID readers and tags may also result in frequency interference and jamming.
- Environmental Considerations: 
  - Be mindful of metal/liquid interference and identify/address external interference sources. Metal and liquids near RFID technologies may result in frequency interference and jamming.
Test 2: To be developed
Brief description of test
- Optimized Tag and Reader Design: 
  - Choose tags with anti-collision features, adjust 
reader sensitivity, and optimize antenna design/placement.
