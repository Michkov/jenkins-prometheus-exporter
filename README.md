This is an experimental prometheus exporter for "pub" that just exposes information about tasks.

This polls pub-hub looking for tasks created since startup and exposes metrics about those tasks
for a prometheus server.

Instead of building on this, we should get a prometheus endpoint added to pub-hub itself, which
would be far less wasteful.