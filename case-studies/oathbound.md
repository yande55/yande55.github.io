# Oathbound: stopping save-code conflicts in a 6-person team

Co-op RPG in a custom C++ engine (team of 6, school project CSD2401 / CSD2451).

**What I owned:** the save and load system for combat and enemies (JSON), plus the engine maths libraries and the enemy AI.

**The problem:** saving kept running into random merge conflicts, because several teammates were editing the same save code at the same time.

**My choice:** I split the save code so that each system saves its own data separately. People stopped editing the same file.

**The result:** the random conflicts stopped.
