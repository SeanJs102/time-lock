I focused on the scheduling transaction functionality, that let users create transactions’
schedules with particular parameters. Furthermore, I added a functionality to display all the
queued transactions and their information including their detail based on event emitters and a
mapping in the Timelock smart contract for holding information of both queued and unqueued
transactions. Apart from that, I also use the filter function on queued transactions such as
filter by status or time.

Real-Time Event Handling: There are event listeners the primary purpose of which is to
update the UI with the current state of the contract.
Efficient Scheduling of Transactions: The components of the transaction scheduling module
are quite solid, enabling users to create transactions that should take place in the future with
the ability to provide details about when the executions should actually occur. This in turn
increases the flexibility of smart contracts since they enable deferred operations.
Transparency & Tracking: Queued transactions and the details of these transactions give users
an idea of what is happening in the background. As for the users, they are able to view all the
queued transactions, which is also useful in tracking the transaction.
Mapping: Storing transaction details through mappings enables a quick search of particular
transactions to either view or dequeue them, or even queue them as needed.
