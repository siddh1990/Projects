# Projects
# Problem Statement:
Company XYZ has 190 personal computers. Each working computer has a 6% probability, independent of all other computers, of encountering a hardware problem on any given day. Most hardware problems require 3/4 of an hour of attention from a computer support technician (CST). 
Each problem that occurs, however, has a 30% chance (independent of all other problems) of developing into a more serious problem requiring an extra 2 hours of attention from a CST. It is assumed that a CST instantly knows whether
a problem is a minor or a major one. 

Each CST can spend up to 6 hours per day fixing problems, and costs the company $300 per day. Every CST hired must be paid their full salary each day, whether or not they have sufficient work to keep them
busy. If the company does not have enough CST’s to solve all the problems occurring on a given day, it hires an outside firm that charges $120 per hour. Computers being fixed by the outside firm are returned to the company by the start of the next day at a fixed delivery cost of $80 (i.e. the delivery cost is
incurred independent of the number of computers delivered.), so that these computers can operate during the next business day. For example, if the company sends two computers to the outside firm on day 1, these two computers will be fixed and returned to Company XYZ at a delivery cost of $80 by the end of day 2, and can be operated on day 3. You can also assume that each computer sent to the outside firm
needs to fixed “from scratch” (i.e., time spent by CST in fixing that computer does not count).

Each computer not in use (e.g., either being fixed by a CST or the outside firm or on the way to be returned) results in a daily loss of $250 in profit for the company.
**The decision variable is to decide whether to hire 1, 2, 3, or 4 CST’s.**

For the same, a simulation has been generated in python to determine the decision variable. It is  assumed that all 190 computers are working properly at the beginning of day 1.

Which option gives the lowest average cost per day? With this number, what is the average
number of hours of support per day we get from the outside firm?
