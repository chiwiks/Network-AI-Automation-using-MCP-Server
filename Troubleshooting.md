## 🔥 Troubleshooting
- [x] Scenario 1
```
Change the mtu of ethernet1 of R1. This will move the ospf neiggbor from FULL adjacency to ExStart.
```
<img width="521" height="49" alt="Image" src="https://github.com/user-attachments/assets/0b4c1f7d-b837-4004-928f-3f304b5ad9ab" />

```
Ask Claude to check and fix the issue
```
https://github.com/user-attachments/assets/f3a04a7d-dc89-4ae7-a72c-e89d0dc004b4

```
From the above video claude logs into the router and changes the mtu to 1500 which fixes the issue
```

- [x] Scenario 2
```
Add Switchport to interface Ethernet1 of R1 with bring down the ospf neighbor because on Arista that will switch the interface to L2
```
<img width="505" height="77" alt="Image" src="https://github.com/user-attachments/assets/9b18be6d-dc70-47be-83d3-fe210270fcf4" />

```
Next ask Claude to troubleshoot and fix the issue

```
https://github.com/user-attachments/assets/923fd542-bb89-4ae0-9146-e63fdfc0deac

```
Claude recognizes the issue and adds the "no switchport" configuration as the video recording above illustrates
```

- [x] Scenario 3
      
```
Change mtu size on ethernet2 of r3 and Bring down the interface with "shutdown" and ask Claude to fix it
```
https://github.com/user-attachments/assets/922faecb-15f4-4ea0-a259-989c752d7a20

```
Claude recognizes both issues and brings up the interface and fixes the mtu to default fixing the ospf neighbor 
```
