# Dungeons and Dragons

Dungeons and Dragons Spell API
Overview
This API provides information on spells in the Dungeons and Dragons world. You can enter a spell name, and the API will give you information such as the spell's description, level, school of magic, and the classes and subclasses that have access to the spell.

Usage
To use this API, make a GET request to the following endpoint:

https://www.dnd5eapi.co/api/spells/${spellName}
Replace {spellName} with the name of the spell you want to search for.

Response
The API will return a JSON object with the following properties:

spell: The name of the spell.
description: A description of the spell's effects.
level: The spell's level.
school: The school of magic the spell belongs to.
classes: An array of classes that have access to the spell.
subclasses: An array of subclasses that have access to the spell.

And some more properties which we will not include at the moment
