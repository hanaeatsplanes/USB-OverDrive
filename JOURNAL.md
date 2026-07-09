# USB OverDrive — Journal Export

Total Time: 7 hours

- Exported at: 2026-07-06T19:14:23Z
- Project ID: 4151
- Entries: 2

## Entry 1
- ID: 10902
- Author: hna
- Created At: 2026-06-01T14:53:00Z

### Content

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ4ODAsInB1ciI6ImJsb2JfaWQifX0=--38a71fd70e69336ca85dfa7a03496d31e22b4265/image.png)

I got started on USB OverDrive, a 4x USB A to USB C hub that I desperately need. I got started on wiring the USBC Port.

### Recording Links

- https://lookout.hackclub.com/api/media/ab3e0b4f-c1d9-4abd-971e-3779129b476f/video.mp4

## Entry 2
- ID: 11378
- Author: hna
- Created At: 2026-06-03T13:37:45Z

### Content

Worked on powering the TUSB chip, added capacitors, changed to 4 layer for easyness, added pull down resistors on PCB
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYzNTEsInB1ciI6ImJsb2JfaWQifX0=--8221a6257e6dc665364414ddbdf207681123621c/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/5371de7c-b3ce-4119-b6cf-2f0ea3e6ad0d/video.mp4

---

# USB OverDrive - Outpost Revive

Total Time: 2h (lookout)

## Day 1: July 6th
Start Time: 3:00 PM
End Time: 12:00 AM
Elapsed Time: 3 hours

I'm gonna restart this project!

I'm gonna remove the 3.0 functionality, i don't particularly care about it since this will only be for mouses and drives and stuff.

<img width="929" height="804" alt="image" src="https://github.com/user-attachments/assets/870cce65-f570-4423-a226-e93d6441bff3" />

looking good :D

time to route! 

<img width="397" height="619" alt="image" src="https://github.com/user-attachments/assets/3b9f95bf-6434-402a-a0c6-df031b0bbfee" />

<img width="550" height="446" alt="image" src="https://github.com/user-attachments/assets/9cddb979-92db-49b9-8494-122473aca957" />

pcbing it

## Day 2: July 7th

<img width="746" height="638" alt="image" src="https://github.com/user-attachments/assets/f4d805a0-7266-4247-ac3f-e460184947f9" />

soo the purple highlighted square is how big maximum this thing can be
and i am very outside that range

i'm gonna have to remove one of the USB's, i dont think i'll be able to make it fit :<

## Day 3: July 8th

all of today i have been suffering with edge.cuts layers. why is kicad so difficult.

anyway, after getting those DRC errors fixed, im starting to work on traces:

<img width="428" height="621" alt="image" src="https://github.com/user-attachments/assets/bbe78109-ba2f-4ceb-bd35-e2a376c95015" />

i have the crystal and power from the upstream(? the one that goes to the laptop) done, so i just need to route D± to the TUSB and route the downstream(?) USBA ones

<img width="107" height="34" alt="image" src="https://github.com/user-attachments/assets/d9b3ad82-556d-4069-a3fb-bf17ea0ab679" />

I finished routing everything!!! omg peak... i did not expect to get this far in today, although i do have some unconnected ground zones whoops... ill fix those tmmr and ship !!!

## Day 3: July 8th

it turns out that JLCPCB doesnt stock the LP5912-1.1DRV... changing it to 1.2V is well within the maximum range that TI is okay with, so i'm doing that
