# Inbox contract

Inbox wires the four owner libraries; it adds no domain state or protocol.
Idle, WaitingForRelease, LiveConversation and ClosedOrOffline are derived views.
No caller-supplied boolean, raw roster or decoded proof DTO grants authority.

Every successful mutation is the child's actual candidate/checkpoint operation.
Contacts/Threads/Delivery/Wallet outputs share the encrypted cwst transaction
before publication or ACK. Failed/uncertain storage returns refusal/reconcile,
never a fresh operation ID, blind retry or fabricated acceptance.

First-contact release needs real Waves/Wallet accepted reservations and current
record checks. Rooms need the Groups/Attend ordered proof capability. Transport
uses complete Mesh messages and existing Records. Missing owner ports remain
unavailable and are separate from facade test or compile success.
