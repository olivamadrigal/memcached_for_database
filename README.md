# cmpe207_hw4_memcached
Caching layer (redis, Memcached, etc..)  for a simple network service (web, database, etc..)

Assigment test the performance improvement when using memcached as opposed to:
recomputing, accessing objects (loading dynamic content from web), and accessing a data store

generate test_data_for_mysql:
test_input: python generate_random_data.py 

terminal: run: memcached

start mysql 

run boaz_test.py # testing script
