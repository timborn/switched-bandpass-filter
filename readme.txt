Thu Jul 20 09:18:21 MST 2023
----------------------------
Ron dropped off a couple of pages of hand drawn sketchs to make into a board.



CHANGE REQUESTS
X. change 4-pin header to 6-pin header
    Ron Taylor, 230719 4:47 PM
    Already thought I’d something. Please make it a 6pin header for the 
    switching so we can reference ground and have a spare too. Thanks
    
    tim born, 230719 4:48 PM
    6 pins instead of 4?  got it
2. correct board size appears to be 82x56mm
X. make sure to label Fx in/out on back of board!
4. DRC "solder mask aperture bridges items with different nets"
   SOT89 for 7805 has no solder bridge between pads for SMT part.
   I turned this error into a warning.  Don't know what I can do 
   to actually fix this.
X. fix this: single branch only using master
X. get rid of traces from front that route on the back
7. spread the connections from Fx in/out to U1 further apart
8. may not need full 15mm width for each of the filter runs
   squeeze them in and let Ron inspect
   we basically have a 56mm width minus SMA connectors minus headers
   there just isn't enough for 4*15mm filter strips
   Resolved: just jam them in.  Ron thinks they will fit.
9. increase board size and add mounting holes in the corners.
   3.25mm plated through and grounded, for 4-40 mounting h/w.
