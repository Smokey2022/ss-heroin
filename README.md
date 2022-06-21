# ss-heroin
Mobile heroin lab using the Journey RV

🔴 Made for the qbcore Framework
- [GitHub](https://github.com/qbcore-framework) / [DISCORD](https://www.discord.gg/qbcore)


Thank you for your interest in my work.
Please consider supporting ❤
- [Paypal ME](https://paypal.me/smokeyscripts22?country.x=US&locale.x=en_US)
- [My TEBEX STORE](https://smokey-scripts.tebex.io/)
- [My city's discord](https://discord.gg/nAKEcGS2pp)

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-inventory](https://github.com/qbcore-framework/qb-inventory)

## Installation
### Manual
1. Place ss-heroin in you're server recources folder and add it to the server.cfg

2. Add these lines below to: qb-core/shared.lua under QBShared.Items
#
	["methlab"] 				 	 = {["name"] = "methlab", 			  			["label"] = "Lab", 						["weight"] = 15000, 	["type"] = "item", 		["image"] = "lab.png", 					["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Stuff to cook!"},
	["painkillers"] 				 	 = {["name"] = "painkillers", 			  			["label"] = "Painkillers", 					["weight"] = 100, 		["type"] = "item", 		["image"] = "painkillers.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Strong pain meds!"},
	["opium"] 				 	 	 = {["name"] = "opium", 			  			["label"] = "Opium", 					["weight"] = 1000, 		["type"] = "item", 		["image"] = "opium.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Stuff to cook!"},
	["heroin"] 				 		 = {["name"] = "heroin", 			  			["label"] = "Heroin", 					["weight"] = 1000, 		["type"] = "item", 		["image"] = "heroin.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Stuff to sell!"},
,

3. Add the images (in ss-heroin/imgs) to qb-inventory/html/images

3. start/restart you're server

## Usage
In you're server give yourself the items above:
5x Painkillers
2x Opium
1x Methlab

And take place in the passenger seat of the JOURNEY, then press E

# Disclaimer
The orginal script is not mine i just made an edit of StolK88's qb-meth to make heroin
Use at your own risk

-Smokey Scripts


# Licence
2022 Smokey Script

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
