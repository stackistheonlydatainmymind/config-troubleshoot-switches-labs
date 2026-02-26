# Lab: learning and clearing mac addresses from mac-table

## 🎯 Objective
how switches learn mac addresses in their mac-table and clear them automatically.


## 📄 Detailed Explanation
Full lab explanation with screenshots is available here:

[Click to View Lab PDF](networking-fundamentals/lab 1  switching - learning mac addresses.pdf)

## 🧠 Concepts Covered
- mac-table 
- switching
- static and dynamic clearing of mac-addresses
- (one extra way of clearing mac addresses) - port security: it is used when mac address is configured by command - switchport port security _mac-address_
  and to clear these mac-address on that switchport use command - clear port-security all
  This is mainly used to prevent switchports from mac address spoofing.
  here, switchport only means that the port is connected to a pc or end user.

## 🛠️ Key Commands Used
--> show mac addr - to show mac-addr table (in global config mode) 
--> do show mac addr (in interface-config mode)
--> clear mac address table-dynamic 
--> clear mac address table-static


