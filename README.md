# NPDS_project
Network	Programming	and	Distributed	Systems
Project	Specification		 25%	of	Module Mark
Due	Week	11
			
Project: Top	Up Phone Implementation
Design	and	develop a distributed	application - Top	Up	Phone	at	Kamarad	Mobile	Operator, as	
described	below.
The	client	can:
! Top	Up	Credit
! Transfer Credit	to	Other	Mobile	Numbers
! Buy	Extra	Options	
! View	Credit	Balance
For	the	Top	Up	Credit,	a	customer	can	specify	the	amount	of	money	to	Top	Up.	
For	 the	 Transfer	 Credit	 to	 Other	Mobile	 Numbers,	 the customer	 can	 specify	 the	 amount	 to	
transfer	and	a	mobile	number	to	transfer	to.	
For	the	Buy	Extra	Options,	the	customer	can	choose	from	the	following	Extra	Options:	
• Kamarad	Talk		Kamarad	100 ( 100	Minutes	in	Kamarad	Network)	– 2 EURO,	
• Kamarad	Talk	Kamarad	500	(500	Minutes	in	Kamarad	Network)	– 8	EURO,	
• Kamarad	Talk	Everyone	100	(100	minutes	to	any	Irish	number)	– 5	EURO,		
• Kamarad	Talk	Everyone	500	(500	minutes	to	any	Irish	number)	– 20	EURO,	
• Kamarad	Internet	1	GB	– 10	EURO,	Kamard	Text	300	(300	texts) – 1	EURO,	
• Kamarad	International	100	(100	Minutes	International)	– 10	EURO.
For	 the	 Transfer	 Credit	 to	 Other	Mobile	 Number/Buy	 Extra	 Options the	 client	 program	will
validate	if	the	customer	has	a	balance	large	enough	to	cover	the	transfer/withdrawal Transfer
Credit	to	Other	Mobile	Number/Buy	Extra	Options.
The	server shall:
- Set	 the	 balance	 of	 the	mobile account(s) to	 zero	 on	 first	 instantiation	 but	 retain	 the	
balance	of	accounts	after	that	thus	demonstrating	persistence	(e.g.	a	SQL	table).
- Provide	functionality	to	return	the	balance	when	requested.	
- Provide functionality	to	Top	Up money	and	thus	increase	the	balance.	
- Provide	functionality	to	Transfer Credit	to	Other	Mobile	Number/Buy	Extra	Options and	
thus	 decrease	 and/or increase	 the	 balances	 of	 different	 accounts. Must	 ensure	
transactions	have	reliability	built	in.	
Network	Programming	and	Distributed	Systems
The	system	should	demonstrate	concurrency	transparency	and	fault	tolerance	by	ensuring	data	
integrity:
- Multiple	clients	should	be	able	to	access/modify	the	same	data	while	ensuring	the data	
remains	consistent
- Transferring	 data	 usually	 decrements	 one	 account	 and	 increments	 another,	 but	 the	
transfer	 is	 not	 complete	 until	 both	 transactions	 have	 happened.	 The	 system	 must	
ensure	that	the	data	is	not	left	in	an	inconsistent	state	should	a	transaction	fail.
The	application	 can	 be	implemented	 using	a	Distributed	Object	Architecure	 (DOA)	i.e.	Object	
Oriented	Middleware	or	by	adopting	a	Service-Oriented	Architecure	(SOA)	i.e.	web	services.
Chose	between	one	of	the	options	and	mention	your	decission	in	the	report.
Marking	Scheme:
DOA or	SOA (90%):
• Top	Up	Credit	– 20%
• Transfer Credit	to	Other	Mobile	Numbers	– 20%
• Buy	Extra	Options	– 20%
• View	Credit	Balance– 20%
• Data	integrity	– 10%
Other (10%):
• Usability – 3.33%
• Presentation – 3.33%
• Code – 3.33%
The	code	should	be	submitted	with	installation	and	run	instruction.	
The	code	should	be	in	a	run	ready	format.	If	the	instructions	or	code	submitted	
do	 not	 allow	 the	 program	 to	 be	 run	 then	 it	 will	 not	 be	 possible	 to	 mark	 the	
project.	
If	the	project	is	only	partially	complete,	as	indicated	by	you	in	the	forms	below	
and	 this	 partial	 functionality	works, then	marks	will	 be	assigned	 based	 on	 the	
functioning	components.
