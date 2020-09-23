# Interview
Material for Mr. Ibrahim and Mr. Raggs

I have created two versions. One with Spring MVC and one as a plain java project using Scanner.

The basis of this project was to use Enumeration as the main point of displaying the state of the vending machine:

(NO_QUARTER, HAS_QUARTER, SOLD, SOLDOUT).

In both projects, the initial price and amount of bottles in the vending machine is set. Each vending machine then would require the (price) amount of coins in order to buy one single bottle. In order to be SOLD, the vending machine has to buy a bottle, and must dispense in order to reach back to NO_QUARTER or SOLDOUT state.

I emphasized the listed states and actions of the vending machine because each developer should develop further versions of vending machines with the similar states, which is the 4 states. In the MVC project, I created a service interface that is implemented by the serviceImpl class, and can be implemented furthermore if there are other 'versions' of vending machines. 


The service/VendingMachine interface requires most importantly to use checkStatus() to check/return the state of the vending machine, and is required to return one of the 4 states (NO_QUARTER, HAS_QUARTER, SOLD, SOLDOUT) to let the user/client know.

Please let me know if there were other features/standards that you wanted me to display if it was missing in this project collection.

Thank you.
