# Notify when device gets connected to the Internet from Background. 
Notify when device gets connected to internet in android pie and lower version.

### For Higher version:-
We have to use JobScheduler because android.net.conn.CONNECTIVITY_CHANGE is deprecated.

### For Lower version:-
We are using android.net.conn.CONNECTIVITY_CHANGE BroadcastReceiver.

