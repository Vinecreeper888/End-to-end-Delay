# End-to-end-Delay


**Computing end to end delay with acknowledgement**

**Name**: Siddhanth M

**USN**: 1KS16CS096

**Invoking the program**:  
   <value in KM> -N <value> -M <value in Mbits> -S <speed in 10^8m/s> -p <processing time in milliseconds>
  
  
**Giving the input:**
Input should be given as: python endtoendfinal.py --t1 10 --t2 12 --d1 2 --d2 1 -N 5 -M 19 -S 2 -p 1
  
  **Program description:**
  The program takes in the input from the command prompt, and then computes the end to end delay for that input.
  The source sends a packet to the router which in turn directs the data packet to the destination. Only when the destination gets the first data packet, it sends an acknowledgement to the source.
  Next, the source sends the next packet of data after receiving the acknowledgement.
  If the acknowledgement is not received, then the source will not send the next packet.
  
  **Challenges faced**
  --> Computing end to end delay
  --> If N(no. of packets) is too large
  --> Transmission delay
  
 
  
