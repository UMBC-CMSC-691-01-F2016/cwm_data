# myfamily_facts.ttl depends on myfamily.n3 and nyfamily_rules.n3

myfamily_facts.ttl : myfamily.n3 myfamily_rules.n3
	cwm -n3 myfamily.n3 -think=hw3_rules.n3 -think=myfamily_rules.n3 > myfamily_facts.ttl

clean :
	rm myfamily_facts.ttl

