Bukkit Plugin Archetype
=======================
This library provides a simplistic archetype for kickstarting your Bukkit projects.

Usage
-----
To generate a new project you will have to execute the following (http://maven.apache.org/)[Maven] command:

	mvn archetype:generate -DarchetypeGroupId=org.evilco.archetype -DarchetypeArtifactId=bukkit-archetype -DarchetypeVersion=1.0 -DgroupId=<your groupId> -DartifactId=<your artifactId>

Where <your groupId> should be replaced with a group id (e.g. your domain name reversed, as example org.evilco.bukkit)
and <your artifactId> should be a project name (as example myBukkitPlugin).

__Please Note:__ You will have to install this archetype via ```mvn install``` before you can generate new projects.

License
-------
__Please Note:__ Projects generated with this archetype are not subject to the license terms below. These terms only
apply to this archetype. Files contained within ```src/main``` are released under Public Domain and thus may be used
as you wish.

	Copyright 2014 Johannes Donath <johannesd@evil-co.org>

	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at

	    http://www.apache.org/licenses/LICENSE-2.0

	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.