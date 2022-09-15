# qb-pizzajob
A Pizza deleivery job made for qb-core, featuring a custom job.

Original Script: https://github.com/ZAUB1/

# Dependencies
- [QBCore](https://github.com/qbcore-framework/qb-core)
- [Pizza Car](https://www.gta5-mods.com/vehicles/foodworks-food-delivery-pack)

# Installation
- Download the Resource & Drag into your resources folder
- Add this to \qb-core\shared\jobs.lua:
```lua
['pizzaboy'] = {
		label = 'Pizza Boy', -- You can change the name of the job
		defaultDuty = true, 
		offDutyPay = false, 
		grades = { 
			['0'] = { 
				name = 'Employee', 
				payment = 50 -- You can change the payment
			}, 
		}, 
	},
```
- Start resource through server.cfg
- Restart your server

# WARNING
- This is my first time scripting so if there is some bugs let me know!
- If you get an error just restart the script with this command: restart qb-pizzajob
