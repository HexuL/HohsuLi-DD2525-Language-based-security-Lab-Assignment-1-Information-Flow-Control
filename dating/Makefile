dating-server:
	$(TROUPE)/bin/troupec dating-server.trp -o ./out/dating-server.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-server.js --id=../ids/id-server.json --trustmap=../trustmaps/server.json --aliases=aliases.json

dating-client_alice:
	$(TROUPE)/bin/troupec dating-client_alice.trp -o ./out/dating-client_alice.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client_alice.js --trustmap=../trustmaps/clientAlice.json --id=../ids/id-clientAlice.json --aliases=aliases.json

dating-client_bob:
	$(TROUPE)/bin/troupec dating-client_bob.trp -o ./out/dating-client_bob.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client_bob.js --trustmap=../trustmaps/clientBob.json --id=../ids/id-clientBob.json --aliases=aliases.json

dating-client_charlie:
	$(TROUPE)/bin/troupec dating-client_charlie.trp -o ./out/dating-client_charlie.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client_charlie.js --trustmap=../trustmaps/clientCharlie.json --id=../ids/id-clientCharlie.json --aliases=aliases.json