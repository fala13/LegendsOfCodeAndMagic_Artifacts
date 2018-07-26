# LegendsOfCodeAndMagic_Artifacts
Codingame hacked and compiled cg-brutaltester and game referee.
I'll upload the sources and pull them to brutaltester later this week.

Example uses:
# just run
java -jar -Dleague.level=4 LegendsOfCodeAndMagic-1.0.jar -p1 "python -u leg.py" -p2 "python -u leg.py" -l ./logs/game1.json

# view game in browser
java -jar -Dleague.level=4 LegendsOfCodeAndMagic-1.0.jar -p1 "python -u leg.py" -p2 "python -u leg.py" -l ./logs/game1.json -s

# execute with 4 games with 2 threads
java -jar .\cg-brutaltester-1.0.0-SNAPSHOT.jar -r "java -jar -Dleague.level=4 LegendsOfCodeAndMagic-1.0.jar"  -p1 "python -u leg.py" -p2 "python -u leg.py" -t 2 -n 4 -s -v -l "./logs/"

Enjoy!

The _info and _trace variants of the referee allow to see from console what is happening during the game etc.
