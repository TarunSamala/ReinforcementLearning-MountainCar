# gym-mountain-car
This repository is a Q-learning implementation of [OpenAI Gym Mountain Car](https://gym.openai.com/envs/MountainCar-v0) game.

The goal is reaching to the flag by using 3 different actions, including 'left', 'nothing', 'right'. However, the force is not enough to reach to the flag just by 'right' action and the agent must use the momentum of car.

# How to use
Just copy-paste the mountain_car_v0.py to your project or clone this repository and run mountain_car_v0.py using python.

# Results
The car reaches to the goal just after a few hundreds of episodes. 

| Episodes  | Output | Output | Output |
| - | - | - | - |
Episode 200, 400, 600 | <img src="https://user-images.githubusercontent.com/20484865/139605337-0a1c6287-f156-4fa0-89c1-8aed90142007.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605337-0a1c6287-f156-4fa0-89c1-8aed90142007.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605338-d1e26c92-7ae6-4430-b614-446f06eca3f1.gif" width="300" height="200"/> |
|||| 
 Episode 800, 1000, 1200 | <img src="https://user-images.githubusercontent.com/20484865/139605339-265071a3-78ea-48a1-9bbd-44e2cb4e09aa.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605340-050538b0-7174-4607-a4bd-4548d43123e8.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605341-975d20d9-d7a6-4881-b254-b986de678e64.gif" width="300" height="200"/> |
|||| 
 Episode 1400, 1600, 1800 | <img src="https://user-images.githubusercontent.com/20484865/139605342-c4fef9d0-a10a-4542-a346-8d68991b4ddd.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605343-0875b2bc-d8b3-4843-bd43-7836afcead14.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605345-d760b90c-7761-4fd0-b434-15ab7e2f89da.gif" width="300" height="200"/> |
|||| 
 Episode 2000, 2200, 2400 | <img src="https://user-images.githubusercontent.com/20484865/139605346-6765f775-9810-4875-9266-326d1769085b.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605347-d237cff5-193a-460f-b440-4417d1ab518d.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605348-cba9f297-b659-4578-a08f-286f46ac153d.gif" width="300" height="200"/> |
|||| 
 Episode 2600, 2800, 3000 | <img src="https://user-images.githubusercontent.com/20484865/139605349-cea55c22-e94b-4d5e-b71f-2f82c7665031.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605351-77e8f7cf-a743-4f0f-ab54-af7259569945.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605352-b6dcd72c-9c1d-4314-a72e-4a6cd5f26e4e.gif" width="300" height="200"/> |
|||| 
 Episode 3200, 3400, 3600 | <img src="https://user-images.githubusercontent.com/20484865/139605353-1a41415d-e229-4ea4-a036-af38e293809d.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605356-67bbd3c0-2a9e-469f-9e60-7eee50756a54.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605357-d290baaa-c8fb-4023-b19e-e0b4ea37df37.gif" width="300" height="200"/> |
|||| 
 Episode 3800, 4000, 4200 | <img src="https://user-images.githubusercontent.com/20484865/139605358-f5760d57-0bcd-48d1-862e-805bb3d0509d.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605359-745b0261-9f7b-4aeb-bc96-b00a59bf62c5.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605360-197074ae-b1cc-432a-9340-fef15d7600d7.gif" width="300" height="200"/> |
|||| 
 Episode 4400, 4600, 4800 | <img src="https://user-images.githubusercontent.com/20484865/139605362-1861a29e-923e-4221-a078-fc48098f8e98.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605363-9a5c2852-0324-4d68-9407-16ce9cfb0d14.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605364-07534e89-2a3a-4e63-bfe4-8d637cc7cf6b.gif" width="300" height="200"/> |
|||| 
 Episode 5000, 5200, 5400 | <img src="https://user-images.githubusercontent.com/20484865/139605365-bb87cd07-0c06-437e-8449-6170e95be381.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605366-07651313-06ff-4b85-97d4-24bfc296f695.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605367-9159d9dc-bd95-4618-9211-dacfe214e7ba.gif" width="300" height="200"/> |
|||| 
 Episode 5600, 5800, 6000 | <img src="https://user-images.githubusercontent.com/20484865/139605368-9ebffc8c-1e86-4cd2-b136-1993344fd40e.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605370-76abcfd5-d8ed-4d23-9134-4e5aab049f16.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605371-94aaec40-40cd-4a1e-ab68-2e496bc99bb3.gif" width="300" height="200"/> |
|||| 
 Episode 6200, 6400, 6600 | <img src="https://user-images.githubusercontent.com/20484865/139605372-e29f4ed3-f089-4e01-a3e5-a912d7f76a35.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605373-030c9aae-50c8-44c0-bd95-aa591b4eeb22.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605374-af07e7aa-f9c9-462f-a8b2-a16ed16f672b.gif" width="300" height="200"/> |
|||| 
 Episode 6800, 7000, 7200 | <img src="https://user-images.githubusercontent.com/20484865/139605375-46b23c49-137b-4f73-84c7-f8e91a96ddee.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605376-edf3e283-c2d5-4d30-84d6-04d3c4e71b5f.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605377-1e1579d8-0ed2-4e5d-8d68-1c519834689d.gif" width="300" height="200"/> |
|||| 
 Episode 7400, 7600, 7800 | <img src="https://user-images.githubusercontent.com/20484865/139605378-878401ef-82bc-42ea-bbce-9b24e60711d3.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605380-35085a13-dfd7-444b-bcd0-e78002612231.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605381-4d417919-3678-4264-95ac-865a6f822422.gif" width="300" height="200"/> |
|||| 
 Episode 8000, 8200, 8400 | <img src="https://user-images.githubusercontent.com/20484865/139605382-a5d72eca-5061-494c-a691-82a59903e3b5.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605383-86d619aa-71bd-49f4-b75a-7cb833237b51.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605384-ef869441-98f1-419c-840c-019d3d089432.gif" width="300" height="200"/> |
|||| 
 Episode 8600, 8800, 9000 | <img src="https://user-images.githubusercontent.com/20484865/139605385-bdbbb4e8-fe22-47ed-a5cc-9bbdf22d1864.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605386-2c262db4-ec59-4da8-b9b9-5af2648dbd5f.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605387-c91a1d86-5677-423b-a903-a05529ff10cf.gif" width="300" height="200"/> |
|||| 
 Episode 9200, 9400, 9600 | <img src="https://user-images.githubusercontent.com/20484865/139605389-9a67118d-dd24-43cf-93fc-4fc6a64e9160.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605390-55ff133e-b490-4210-bea8-83932600a649.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605391-fdf24507-e0c7-4913-96dd-9ffca4e27da7.gif" width="300" height="200"/> |
|||| 
 Episode 10000, 10200, 10400 | <img src="https://user-images.githubusercontent.com/20484865/139605393-1fcbf0c0-4b80-40e8-a770-1208a2cc7e6d.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605394-16b16586-0890-4b0e-9862-7891b4384a6d.gif" width="300" height="200"/> | <img src="https://user-images.githubusercontent.com/20484865/139605395-c63a9f7b-b298-4591-a252-bab415e6af4e.gif" width="300" height="200"/>


