# omron-tcp

TBD:
- [ ] folders
- [ ] add .3dm magnet
- [ ] electromagnet shema
- [ ] printscreens from TM Flow
- [ ] GIF from RoboDK
- [ ] *several path nodes
- [ ] *modbus Python
- [ ] *TM Flow remote
- [ ] *Omron Digital IO
- [ ] *ROS
- [x] *Head: Pen holder
- [x] *Head: Electromagnet
- [ ] *Head: Paste extruder
- [ ] *Head: weaver
- [ ] *Head: hot wire fork
- [ ] *Head: soft gripper
- [ ] *Head: endmill
- [ ] *Head: led stick


[Docs RoboDK](https://docs.google.com/document/d/1Lc5LTBMNgVjAjmmiBWO0JbGHVVClJnMz1acDogzbXbs/edit)

Rhino to RoboDK:

![frame](https://github.com/m112521/omron-tcp/assets/85460283/a2859adc-4c3c-406c-9fb4-0284cdbe5613)


If program is generated with "Omron" postrpocessor, then too many points in NURBS makes it impossible to run program in TM Flow - it simply crashes. 
If program is generated as "PathNode" postrpocessor - only first curve's points are being saved. 

![SeparateHead](https://github.com/m112521/omron-tcp/assets/85460283/db7a606e-f19f-4e26-8a3a-3d77f3341ec7)


![Group 201](https://github.com/m112521/omron-tcp/assets/85460283/9e4bbf00-c4ed-4b9a-aacb-c505caaa1320)

TW-Flow:

![20231208_193448](https://github.com/m112521/omron-tcp/assets/85460283/a129825b-c9d1-4ad6-a146-4f6278d75140)


Resulted in: 

![20231208_200423](https://github.com/m112521/omron-tcp/assets/85460283/ae4d4f18-5896-4b7f-b2b3-55233263672d)


PenHolder in action:

https://github.com/m112521/omron-tcp/assets/85460283/3d6b2661-0ad3-402b-9e8d-cb1eeffdee72

