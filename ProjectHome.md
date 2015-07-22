memcached is a high-performance, distributed memory object caching system, generic in nature, but intended for use in speeding up dynamic web applications by alleviating database load.

Danga Interactive developed memcached to enhance the speed of LiveJournal.com, a site which was already doing 20 million+ dynamic page views per day for 1 million users with a bunch of webservers and a bunch of database servers. memcached dropped the database load to almost nothing, yielding faster page load times for users, better resource utilization, and faster access to the databases on a memcache miss.

Please see [memcached.org](http://memcached.org) for the latest release information.